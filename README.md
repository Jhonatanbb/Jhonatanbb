# Install required dependencies
pkg install git python

# Clone Sherlock repository
git clone https://github.com/sherlock-project/sherlock.git

# Navigate to directory
cd sherlock

# Install Python dependencies
pip install -r requirements.txt

# Make the script executable (optional)
chmod +x sherlock.py

# Run Sherlock
python sherlock.py Fabiana Jaques 
