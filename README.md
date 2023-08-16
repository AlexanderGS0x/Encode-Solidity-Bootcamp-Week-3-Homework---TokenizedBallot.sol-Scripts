# Encode-Solidity-Bootcamp-Week-3-Homework-TokenizedBallot.sol-scripts
Develop and run scripts for “TokenizedBallot.sol” within your group to give voting tokens, delegating voting power, casting votes, checking vote power and querying results.

The Plan
Contract Purpose:
- `MyToken` in `ERC20Votes.sol` is the token that gives voting power
- `TokenizedBallot.sol` is the contract voters will interact with to vote

Pre-work:
- Come up with a list of proposals to pass when initiating `TokenizedBallot.sol` ✅
    - Online book club reading themes
        1. Historical Fiction
        2. Self-Help
        3. Fantasy Worlds
        4. Classic Literature

Steps
- Complete `TokenizedBallot.sol` ✅
    - add event to be emited when a vote is cast ✅
- List each script that will need to be written ✅
- Sudo code these scripts ✅
- Group members write scripts ✅

Final Homework Goal:
- Deploy `ERC20Votes.sol` (only one member needs to deploy. This member will be have "MINTER_ROLE") ✅
    - Member with "MINTER_ROLE" will mint and send tokens to other members. ✅
    - Each member will need to self delegate ✅
- Deploy `TokenizedBallot.sol` (only one member needs to deploy) ✅
- Record transactions for following actions:
    - Deploy `ERC20Votes.sol` ✅
    - "MINTER_ROLE" mints tokens to members ✅
    - Self-delgation ✅
    - Deploy `TokenizedBallot.sol` ✅
    - Members vote ✅
    - call `winnerName()` ✅
