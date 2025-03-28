# Creates a new virtual environment in the .venv directory
python -m venv .venv

# Activate the Virtual Environment
source .venv/bin/activate

# Install packages 
pip install <dependencies>

# Set Environment varable
export <EnvVariable>=<EnvValue>
python main.py

python -m venv .venv && source .venv/bin/activate && python main.py

# Deactivate the Virtual Environment
deactivate
