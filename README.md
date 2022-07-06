# jieba-wasm-html
Fast Jieba Chinese text segmentation on browser. No need for backend; No need for NPM.
基于 WebAssembly 结巴分词实现的纯前端分词服务, 只需浏览器无需npm

## Demo

https://cxumol.github.io/jieba-wasm-html/

## Benchmark

About **45x faster** than a typical Python Jieba web app. Details can be found at <https://github.com/cxumol/jieba-wasm-html/issues/1>

## How to use Jieba WebAssembly on browser or Deno without installing npm?

Check out [this blog post]()

## Future plan

Pull requests are welcomed! <s>Otherwise gugugu</s>

- [ ] User can choose to load different example text from corpus
- [ ] Enable more Jieba-wasm functions `cut_all, cut_for_search, tokenize, add_word`
- [ ] Implement your brilliant new idea

## Acknowledgement

- https://github.com/fengkx/jieba-wasm
- https://app.gumble.pw/jiebademo/