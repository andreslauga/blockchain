# Blockchain project

Single-file project written in Python that I did during a Blockchain course.
This was helpful for me to acquire the main Blockchain concepts.
It runs on a local Flask server and can be used through Postman by making requests to specific endpoints.

## Disclaimer

**I'm not the author of this app**. I just followed the tutorial to learn the concepts and practice Python.
This project is part of the awesome course [_Curso Completo de Blockchain de cero a experto_](https://www.udemy.com/course/curso-completo-de-blockchain-de-la-a-a-la-z/) by **Joan Amengual** and **Juan Gabriel Gomila Salas**. It's in Spanish :)

## Test this app

Prerequisites: You will need Python and Postman to be installed on your pc.

1. Clone this repo.
2. Execute blockchain.py using the run button in Visual Studio Code, or the command line:
`$ python blockchain.py `
3. In Postman, import the collection from [this link](https://www.getpostman.com/collections/8a803fe0e8f7810867ba)
4. Play around with the endpoints: Mine some blocks, get the chain, and see how the blocks were added to it and last but not least, validate the chain!

## Available endpoints:
* 0.0.0.0:5000/mine_block
* 0.0.0.0:5000/get_chain
* 0.0.0.0:5000/valid
