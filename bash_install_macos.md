brew install bash



# Check installation location

ls "$(brew --prefix)/bin/bash" 


# append to /etc/shells

ls "$(brew --prefix)/bin/bash" | sudo tee -a  /etc/shells

# change to bash

chsh -s "$(brew --prefix)/bin/bash"