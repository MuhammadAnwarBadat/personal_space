# personal_space

https://docs.google.com/spreadsheets/d/1eJ4iWWi409UNSeBrNteMf7FpN61sDy4hycZ0rVuyDHg/edit#gid=0 

# How to deploy an LLM Model

https://winder.ai/part-4-deploy-chatgpt-model-llm/
https://gaper.io/deploy-custom-llm-applications/

LLM	Strengths	Weaknesses	Pricing	Website
Cohere	Text generation, search & understanding, conversation	Limited transparency, cost for private/on-premise	Public/private cloud options, custom quotes	"https://lablab.ai/tech/cohere 
https://cohere.com/ 
https://cohere.com/pricing "

GPT-3.5	Creative text formats, essay writing	Overhyped, can be biased	Pay-per-use, tiered pricing	"https://lablab.ai/tech/openai/gpt3-5  
https://lablab.ai/tech/openai/gpt3   
https://platform.openai.com/docs/models/gpt-3 
https://platform.openai.com/docs/models/gpt-3-5 
https://platform.openai.com/docs/models/gpt-4-and-gpt-4-turbo "

PaLM 2 (Bison-001)	Reasoning, logic, math, advanced coding	Expensive, limited access	Limited public access, research partnerships	"https://lablab.ai/tech/google/palm 
https://ai.google/discover/palm2/ 
https://cloud.google.com/vertex-ai/docs/generative-ai/pricing "

Claude v1	Helpfulness, honesty, harmlessness	Still under development	Pay-per-use	https://www.anthropic.com/index/introducing-claude 
Falcon	Accuracy, fluency in text generation	Open-source only	Free (open-source)	"https://lablab.ai/tech/tiiuae/falcon-llm
https://falconllm.tii.ae/ "

LLaMA & derivatives	Research purposes, various sizes & strengths	Research-oriented, not all sizes publicly available	Free (research access, some models), commercial use licenses	https://lablab.ai/tech/meta/llama https://lablab.ai/tech/meta/llama-2 

autogpt	Flexibility, accessibility, community	Limited support, community-driven	Pay-per-use	https://huggingface.co/spaces/aliabid94/AutoGPT https://lablab.ai/tech/autogpt 

Yi Series	Factual language tasks, open access	Smaller model size compared to some	Free (research access), commercial licenses	"https://lablab.ai/tech/yi-llms 
https://huggingface.co/TheBloke/Yi-34B-GGUF "

Vectara	Search accuracy, relevance, multilingual	Primarily search-focused	Pay-per-use, custom quotes	"https://lablab.ai/tech/vectara 
https://www.vectra.ai/ "

Gorilla	API integration, task automation, code generation	Requires API integration expertise	Pay-per-use	"https://lablab.ai/tech/gorilla
https://gorilla.cs.berkeley.edu/ "

LangChain	Modular, developer-friendly, open-source	New, evolving concept	Free (open-source)	"https://lablab.ai/tech/langchain 
https://www.langchain.com/ "

### Huggingface credentials

### https://huggingface.co/login
anwarbadat1997.ab@gmail.com \m
xg!@8aBjLDm;zk/

# Configuring Github using Git Bash

git config --global user.name "Your User Name"
git config --global user.email "Your Email"
git config --list

# Clone and Status

Clone - Cloning a repository on your local machine
git clone <add link of remote repo here>

Status -  Displays the state of the code
git status

# There are 4 status of files in Github

1. untracked - Files which are not tracked by Git yet
2. modified - changes tracked by Git
3. staged - files are ready to be committed
4. unmodified - unchanged files, nothing to commit

# Add and Commit

add - adds new or changed files in your working localise directory to the Git staging area
git add <file name> (for specific file)
git add . (for all the files in the directory)

commit - it's a comment or record of change
git commit -m "Put your comments inside these parenthesis"

# Push Command

push - upload local files to remote repository
git push origin main (main is not by default by default is master you have to change it to main)

# Init Command

init - used to create new Git repo 

git init
git remote add origin <Put your remote repo link here>
git remote -v (to check or verify remote repo)
git branch (to check which branch you are at)
git branch -M main (to rename branch)
git push origin main

# Branch Commands

git branch (to check branch)
git branch -M main (to rename branch)
git checkout <write branch name here> (to navigate between the brnaches)
git checkout -b <write name of new branch here> (to create a new branch)
git branch -d <write branch name here> (to delete a branch)

# Merging Code

Way 1:
git diff <write branch name here> (to compare commits, branches, files and more)
git merge <write branch name here> (to merge two branches)

Way 2:
Create a pull request
