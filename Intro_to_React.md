| **Phân loại**         | **Tên Snippet**                         | **Prefix (Gọi)** | **Kết quả Code Được Tạo ra (Output)**                                            |
| --------------------- | --------------------------------------- | ---------------- | -------------------------------------------------------------------------------- |
| **COMPONENTS**        | React Functional Component              | `rfc`            | `function ComponentName() { return ( <div></div> ); }`                           |
|                       | Arrow Function Component                | `rsc`            | `const ComponentName = () => ( <div></div> );`                                   |
|                       | Arrow Function Component (Destructured) | `rscd`           | `const ComponentName = ({ propName }) => { return ( <div>{propName}</div> ); };` |
|                       | React Fragment                          | `rf`             | `<></>`                                                                          |
| \---                  | \---                                    | :---             | :---                                                                             |
| **HOOKS (STATE)**     | useState Hook                           | `rus`            | `const [state, setState] = useState(initialValue);`                              |
|                       | useState Functional Update              | `rusf`           | `setState((prevStat) => prevStat + 1);`                                          |
|                       | useState Object Update                  | `ruso`           | `setUser({ ...currentUser, key: value });`                                       |
| \---                  | \---                                    | :---             | :---                                                                             |
| **RENDERING**         | Render Map (List)                       | `rmap`           | `{items.map((item, i) => ( <div key={i}></div> ))}`                              |
|                       | Render Ternary (If-Else)                | `rt`             | `{condition ? "TrueValue" : "FalseValue"}`                                       |
|                       | Render Logical AND (If)                 | `ra`             | `{condition && <div>Rendered</div>}`                                             |
| \---                  | \---                                    | :---             | :---                                                                             |
| **EVENTS & PROPS**    | Event Handler with Arguments            | `rea`            | `onClick={() => functionName(params)}`                                           |
|                       | Spread Props                            | `rsp`            | `{...props}`                                                                     |
|                       | JSX Comment                             | `rc`             | `{/* Comment here */}`                                                           |
| \---                  | \---                                    | :---             | :---                                                                             |
| **STYLED COMPONENTS** | Styled Component                        | `rs`             | `const ComponentName = styled.div` `/* CSS here */`                              |
|                       | Styled Props Logic                      | `rsprop`         | \`property: ({ propName }) => propName                                           |
