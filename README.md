# VoiceCord
Keep your Discord account online in voice channels 24/7.

## Disclaimer: 
 This project breaks Discord’s rules and may get your account banned. 

## Warning: 
 Don’t share your Discord token with anyone, as it lets them access your account, including bypassing two-factor authentication (2FA) and your password.

## Requirements
- Python 3.8 or higher

## Installation

1. **Clone the repository** (or download the script):
    ```bash
    git clone https://github.com/i5ms/VoiceCord.git
    cd VoiceCord
    ```

2. **Install the required dependencies** using `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

3. **Replace `Your_Token_Here`** in the script with your actual discord account token.

4. **Replace `1111111111111111111`** in the script with the actual ID of the voice channel you want the account to connect to.

## Usage

Run the bot script:

```bash
python main.py
```

### Notes

- Ensure that account has the necessary permissions to connect to the voice channel.

### Troubleshooting

- **Account not connecting to the voice channel**: Double-check the channel ID and the account's permission.
- **Script not running**: Ensure that your Python environment is set up correctly and all dependencies are installed.
