
# ChunkArray

#### ChunkArray is a lightweight JavaScript library that provides functionality for splitting arrays into smaller chunks. It allows you to break down large arrays into more manageable pieces, which can be useful for tasks like pagination, batching data processing, or any scenario where you need to work with data in smaller portions.

# Installation
####  You can install ChunkArray via npm:

```
npm i divide-array-bitt

```
# Usage
```
const ChunkArray = require('divide-array-bitt');

const myArray = [1, 2, 3, 4, 5, 6, 7, 8, 9];
const chunkSize = 3;

const chunks = ChunkArray.chunk(myArray, chunkSize);
console.log(chunks);
// Output: [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
```