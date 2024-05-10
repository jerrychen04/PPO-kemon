# PPokemon Showdown

# To run a server
- Install Node.js v10+.

Clone the Pokémon Showdown repository and set it up:

- git clone https://github.com/smogon/pokemon-showdown.git
- cd pokemon-showdown
- npm install
- cp config/config-example.js config/config.js
- node pokemon-showdown start --no-security

# To run sample RL code
- Install anaconda3 and add to PATH
- Link is here: https://www.geeksforgeeks.org/how-to-setup-anaconda-path-to-environment-variable/
- Create a conda env and install poke-env==0.4.21 
- Install all other dependencies needed (will add requirements.txt later)
- Run python [model_name].py to train the model

Sample code from this repo: https://github.com/leolellisr/poke_RL
Environment: https://github.com/hsahovic/poke-env

```
@misc{poke_env,
    author       = {Haris Sahovic},
    title        = {Poke-env: pokemon AI in python},
    url          = {https://github.com/hsahovic/poke-env}
}
```