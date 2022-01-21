{
    "autosave": true,
    "cpu": true,
    "opencl": false,
    "cuda": false,
    "pools": [
        {
            "coin": "monero",
            "url": "127.0.0.1:18081",
            "user": "48AgL3yX4J7XFFZzjyeiLM2bNmm1GdfRcTvFykDWZCN1PGWGRZQfHvgChKWUFKUAiuShYBa9baRcKEgJQC7jERN44tRGNHY",
            "daemon": true
        }
    ]
}

./xmrig -o 127.0.0.1:18081 -u 48AgL3yX4J7XFFZzjyeiLM2bNmm1GdfRcTvFykDWZCN1PGWGRZQfHvgChKWUFKUAiuShYBa9baRcKEgJQC7jERN44tRGNHY --coin monero --daemon
