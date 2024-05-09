# PPokemon Showdown

# To run a server
-Install Node.js v10+.

Clone the Pokémon Showdown repository and set it up:

-git clone https://github.com/smogon/pokemon-showdown.git
-cd pokemon-showdown
-npm install
-cp config/config-example.js config/config.js
-node pokemon-showdown start --no-security

# To run sample RL code
-Install anaconda3 and add to PATH
-Modify dependencies.yml prefix: C:\Users\[CHANGE TO PC USERNAME]\anaconda3\envs\poke_env3
-conda env create -f dependencies.yml
-conda activate poke_env3
-do the #to run a server steps
-python ppo.py to train and eval the sample ppo.py 

Sample code from this repo: https://github.com/leolellisr/poke_RL
Environment: https://github.com/hsahovic/poke-env
