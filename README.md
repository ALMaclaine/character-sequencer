# character-sequencer

## install

`npm install character-sequencer`

## usage

```javascript
const CharacterSequencer = require('character-sequencer');
const seq = new CharacterSequencer();
console.log(seq.next());
```

or with custom characters

```javascript
const CharacterSequencer = require('character-sequencer');
const seq = new CharacterSequencer(['12345789abcd']);
console.log(seq.next());
```
