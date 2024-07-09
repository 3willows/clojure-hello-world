- Follow along [this tutorial](https://www.youtube.com/watch?v=MQmdWSh2FG4&list=PLaGDS2KB3-ArG0WqAytE9GsZgrM-USsZA&index=6)

- Starta app.cljs with the following command in terminal

```bash
clj -M -m cljs.main --compile app --repl
```

- In the repl type

  - (js/console.log"hello again")
  - (js/console.log(+ 1 2 3))
  - (js/console.log(document.getElementsByTagName "p"))

- To watch for changes in app, try instead 

```bash
clj -M -m cljs.main --
watch src --compile app  --repl
```