# This page explains how to install ollama in PC with Linux OS #

### - Note ###

You should have at least 8 GB of RAM available to run the 7B models, 16 GB to run the 13B models, and 32 GB to run the 33B models.

### -For installing Olalama ###

``` curl -fsSL https://ollama.com/install.sh | sh ```

### -For installing Model - I have chosen small model - not to kill my machine ###

```  ollama run llama3.2:1 ```  -- SLM with 1 B

 ``` ollama run llama4:scout ```  -- LLM with 109B 

### -Working with Ollama ###

 ``` sudo systemctl stop ollama ``` (to stop)

 ``` sudo systemctl start ollama ``` (to start it manually)

 ``` sudo systemctl status ollama ``` (to check if it's running)

### - Run / Intercat with Olama ###

  ``` ollama run llama3.2:1b "Who are you" ```

#### Response could be - I'm an artificial intelligence model known as Llama. Llama stands for "Large Language Model Meta AI."####

## Visit the link for Ollama git page ##

  https://github.com/ollama/ollama

## For full list of model libraries ## 

  https://github.com/Nagarc/oreilly_slm/blob/main/groundup.md
