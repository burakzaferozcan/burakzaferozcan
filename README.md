- 👋 Hi, I’m BZO, and I'm on my way to becoming a 'JS Man'.

```
const getStack = () => {
  return {
    MEVN_STACK: ["MongoDB", "ExpressJS", "VueJS", "NodeJS"],
  };
};
console.log(
  `I’m currently learning : ${getStack()
    .MEVN_STACK.map((tech) => {
      return Object.values(tech);
    })
    .join(" ")}`
);
```
