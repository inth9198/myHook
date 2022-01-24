import "./styles.css";
import React, { useState } from "react";
import ReactDOM from "react-dom";

function useInput(defaultValue) {
  const [value, setValue] = useState(defaultValue);
  const onChange = (e) => {
    const {
      target: { value }
    } = e;
    setValue(value);
  };
  return { value, onChange };
}

export default function App() {
  const name = useInput("");
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <br />
      <input {...name} placeholder="wun" />
      <h2>Start editing to see some magic happen!</h2>
    </div>
  );
}
