# Create a Modelfile
@"
FROM qwen2.5-coder:7b
PARAMETER num_ctx 4096
"@ | Out-File -FilePath Modelfile -Encoding utf8

# Create a custom model with this config
ollama create qwen2.5-coder-7b-4k -f Modelfile