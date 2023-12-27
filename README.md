An Apollo standalone Graphql server used as backend for frontend exercise [Phonebook-react-apollo](https://github.com/pcolt/Full-stack-open_part7-phonebook-react-apollo).
Exercise from Helsinki Univeristy's course [Open Full Stack - part 8/a](https://fullstackopen.com/en/part8/graph_ql_server).

## Installation

`git clone`  
`npm install`   

##### Configure secret/environment variables
- In the root folder create `.env` file with following keys:   
```
MONGODB_URI = 'mongodb+srv://fullstack:MONGODB_FULLSTACK_USER_PASSWORD@cluster0.ck2n2.mongodb.net/repos?retryWrites=true&w=majority'
JWT_SECRET = 'secret'
```

## Usage

`npm start` serving on http://localhost:4000