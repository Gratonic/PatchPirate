# PatchPirate
Github Recon/OSINT Software for finding personal email adresses 

PatchPirate is a Recon/OSINT software for mass processing GitHub commit and repo data to find unintentionally exposed private email addresses from a GitHub username or account via the GitHub API.

## Instalation and use
Requires python 3.11+ with pip.

To install PatchPirate on Linux run: `git clone https://github.com/FailurePoint/PatchPirate.git & cd PatchPirate & python3 -m pip install -r requirements.txt`
To run it, from the folder it is installed in run: `python3 patchpirate.py`

## Usage and rate limmits
Usage is self obvious... please dont ask me how to use it... just use your brain for 30 secconds. it's not that hard.

GitHub imposes a rate limmit on unauthenticated users for API access of 60 requests/hr. the usage of the API varies per scan, but is roughly the same as the amount of public repos the target maintains.
If 60 requests is not going to be enough, you can authenticated using a Personal Acess Token (PAT) and unlock up to 5000 requests an hour. [How do I get one](https://www.geeksforgeeks.org/how-to-generate-personal-access-token-in-github/)?

## Screenshots
Coming soon.


