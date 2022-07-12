# jieba-wasm-html
Fast Jieba Chinese text segmentation on browser. No need for backend; No need for NPM. Code works well on Deno, too.

结巴中文分词网页版, 基于 WebAssembly 的纯前端实现; 亦可用于 Deno

## Demo

https://cxumol.github.io/jieba-wasm-html/

## Benchmark

About **45x faster** than a typical Python Jieba web app. Details can be found at <https://github.com/cxumol/jieba-wasm-html/issues/1>

## Technical information

Check out this blog post [How to use Jieba WebAssembly on browser or Deno without installing npm?](https://xirtam.cxumol.com/browser-wasm-jieba/)

## Future plan

Pull requests are welcomed! <s>Otherwise gugugu</s>

- [ ] User can choose to load different example text from corpus
- [ ] Enable more Jieba-wasm functions `cut_all, cut_for_search, tokenize, add_word`
- [ ] Implement your brilliant new idea

## Acknowledgement

- https://github.com/fengkx/jieba-wasm
- https://app.gumble.pw/jiebademo/
