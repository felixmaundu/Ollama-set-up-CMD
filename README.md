# Ollama-set-up-CMD
To get the full list of LLMs installed

 -  ollama list 

 ## To Install and run

    ollama run mixtral
    ollama run mistral
    ollama run llama2
## available deepseek versions
    ollama run deepseek-coder
    ollama run deepseek-coder:instruct
    ollama run deepseek-llm
    ollama run deepseek-r1




You can also check for running background processes if needed:

On Windows (PowerShell or CMD):

    tasklist | findstr ollama

If you want to fully shut it down (not just a model), you can stop the Ollama server like this:

    taskkill /F /IM ollama.exe
