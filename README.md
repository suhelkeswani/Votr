[<img src="https://i.imgur.com/INx6BmV.png">](https://www.youtube.com/watch?v=w_4B_jSe5vw)
*Click the image for a Brief YouTube Demo of the Project!*

# Votr
Votr is a proof-of-concept for a secure and accessible online election which utilizes blockchain technology to maintain an immutable and anonymous record of verified ballots.
Votr was a project submission for Georgia Tech's 2021 HackGT Hackathon and won 3rd place in the NSA Secure Code challenge.

Votr models the process of a blockchain election by utilizing python to implement a blockchain mechanism which stores online ballot data. Users are able to view the blockchain, cast a vote if they are registered, and lookup the record of their ballots through their block number containing their transaction. After a voter votes, their voter hash is removed from the registered voters, and added to a blacklisted voter hash collection in order to prevent voting more than once.

## Setup
1. Using pip, install the Django REST framework by running 
```
pip3 install djangorestframework
```
2. Using npm, install Node.js by running
```
npm install
``` 
3. Start the backend Django Server by running
```
python3 manage.py runserver
``` 
4. Create a React Build by running
```
npm run build
```
5. Go to [localhost:8000](localhost:8000) to access the client side web app.

## Post-Hackathon Submission Updates
12/22/2021: A client side page where users can register to vote was added.
