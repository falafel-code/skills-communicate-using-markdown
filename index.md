# Hello 👋

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


// A simple React functional component
```
import React, { useState } from 'react';

function Greeting({ initialName }) {
  const [name, setName] = useState(initialName);

  const handleChange = (e) => {
    setName(e.target.value);
  };

  return (
    <div>
      <h1>Hello, {name}!</h1>
      <input value={name} onChange={handleChange} />
    </div>
  );
}

export default Greeting;
```
