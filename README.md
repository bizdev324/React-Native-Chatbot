# React Simple Chatbot

<a href="https://travis-ci.org/LucasBassetti/react-simple-chatbot"><img src="https://travis-ci.org/LucasBassetti/react-simple-chatbot.svg?branch=master" alt="Travis CI" /></a> <a href="https://badge.fury.io/js/react-simple-chatbot"><img src="https://badge.fury.io/js/react-simple-chatbot.svg" alt="npm version"></a>
  <img src="https://codecov.io/gh/LucasBassetti/react-simple-chatbot/branch/master/graph/badge.svg" alt="Codecov" />
</a> <a href="https://beerpay.io/LucasBassetti/react-simple-chatbot"><img src="https://beerpay.io/LucasBassetti/react-simple-chatbot/badge.svg?style=flat" /></a>

A simple chatbot component to create conversation chats

<img src="https://cloud.githubusercontent.com/assets/1014326/25716667/2d4bb4c4-30d6-11e7-996e-30c8fb316361.gif" height="400" />

## Getting Start

```bash
npm install react-simple-chatbot --save
```

## Usage


``` javascript
import ChatBot from 'react-simple-chatbot';

const steps = [
  {
    id: '0',
    message: 'Welcome to react chatbot!',
    trigger: '1',
  },
  {
    id: '1',
    message: 'Bye!',
    end: true,
  },
];

ReactDOM.render(
  <div>
    <ChatBot steps={steps} />
  </div>,
  document.getElementById('root')
);
```



