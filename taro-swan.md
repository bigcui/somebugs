 build failed (from ./node_modules/babel-loader/lib/index.js):
SyntaxError: /Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/taro-ui-vue/src/components/tabs/index.ts: Unexpected reserved word 'interface'. (10:0)

   8 | const MAX_INTERVAL = 10
   9 |
> 10 | interface Style {
     | ^
  11 |   [key: string]: string | number
  12 | }
  13 |
    at Parser._raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:134:45)
    at Parser.raiseWithData (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:129:17)
    at Parser.raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:78:17)
    at Parser.checkReservedWord (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:2397:12)
    at Parser.parseIdentifierName (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:2336:12)
    at Parser.parseIdentifier (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:2306:23)
    at Parser.parseExprAtom (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:998:25)
    at Parser.parseExprSubscripts (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:603:23)
    at Parser.parseUpdate (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:583:21)
    at Parser.parseMaybeUnary (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:550:23)
    at Parser.parseExprOps (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:354:23)
    at Parser.parseMaybeConditional (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:320:23)
    at Parser.parseMaybeAssign (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:281:21)
    at Parser.parseExpressionBase (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:207:23)
    at callback (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:200:39)
    at Parser.allowInAnd (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:2631:16)
 @ ./node_modules/taro-ui-vue/src/components/tabs/index.vue?vue&type=script&lang=js& (./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./node_modules/taro-ui-vue/src/components/tabs/index.vue?vue&type=script&lang=js&) 59:0-29 62:11-17
 @ ./node_modules/taro-ui-vue/src/components/tabs/index.vue?vue&type=script&lang=js&
 @ ./node_modules/taro-ui-vue/src/components/tabs/index.vue
 @ ./node_modules/taro-ui-vue/src/index.js
 @ ./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./node_modules/@tarojs/taro-loader/lib/raw.js!./src/pages/index/index.vue
 @ ./src/pages/index/index.vue,./node_modules/taro-ui-vue/src/components/tag/index.ts
Module build failed (from ./node_modules/babel-loader/lib/index.js):
SyntaxError: /Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/taro-ui-vue/src/components/tag/index.ts: Unexpected token, expected "," (82:21)

  80 |   },
  81 |   methods: {
> 82 |     handleClick(event: CommonEvent): void {
     |                      ^
  83 |       if (!this.disabled) {
  84 |         this.onClick &&
  85 |           this.onClick(
    at Parser._raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:134:45)
    at Parser.raiseWithData (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:129:17)
    at Parser.raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:78:17)
    at Parser.unexpected (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/util.js:181:16)
    at Parser.expect (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/util.js:145:28)
    at Parser.parseBindingList (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/lval.js:315:14)
    at Parser.parseFunctionParams (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:1207:24)
    at Parser.parseMethod (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:2034:10)
    at Parser.parseObjectMethod (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:1880:19)
    at Parser.parseObjPropValue (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:1952:12)
    at Parser.parsePropertyDefinition (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:1803:10)
    at Parser.parseObjectLike (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:1671:25)
    at Parser.parseExprAtom (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:1098:21)
    at Parser.parseExprSubscripts (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:603:23)
    at Parser.parseUpdate (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:583:21)
    at Parser.parseMaybeUnary (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/expression.js:550:23)
 @ ./node_modules/taro-ui-vue/src/components/tag/index.vue?vue&type=script&lang=ts& (./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./node_modules/taro-ui-vue/src/components/tag/index.vue?vue&type=script&lang=ts&) 1:0-28 2:15-20
 @ ./node_modules/taro-ui-vue/src/components/tag/index.vue?vue&type=script&lang=ts&
 @ ./node_modules/taro-ui-vue/src/components/tag/index.vue
 @ ./node_modules/taro-ui-vue/src/index.js
 @ ./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./node_modules/@tarojs/taro-loader/lib/raw.js!./src/pages/index/index.vue
 @ ./src/pages/index/index.vue,./node_modules/taro-ui-vue/src/components/textarea/index.ts
Module build failed (from ./node_modules/babel-loader/lib/index.js):
SyntaxError: /Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/taro-ui-vue/src/components/textarea/index.ts: Missing semicolon. (6:4)

  4 | import { pxTransform } from '../../utils/common'
  5 |
> 6 | type ExtendEvent = {
    |     ^
  7 |   target: {
  8 |     value: string
  9 |   }
    at Parser._raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:134:45)
    at Parser.raiseWithData (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:129:17)
    at Parser.raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:78:17)
    at Parser.semicolon (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/util.js:138:10)
    at Parser.parseExpressionStatement (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:886:10)
    at Parser.parseStatementContent (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:374:19)
    at Parser.parseStatement (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:229:17)
    at Parser.parseBlockOrModuleBlockBody (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:961:25)
    at Parser.parseBlockBody (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:937:10)
    at Parser.parseProgram (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:116:10)
    at Parser.parseTopLevel (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:101:25)
    at Parser.parse (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/index.js:41:10)
    at parse (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/index.js:26:26)
    at parser (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/core/lib/parser/index.js:52:34)
    at parser.next (<anonymous>)
    at normalizeFile (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/core/lib/transformation/normalize-file.js:82:38)
 @ ./node_modules/taro-ui-vue/src/components/textarea/index.vue?vue&type=script&lang=ts& (./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./node_modules/taro-ui-vue/src/components/textarea/index.vue?vue&type=script&lang=ts&) 1:0-33 2:15-25
 @ ./node_modules/taro-ui-vue/src/components/textarea/index.vue?vue&type=script&lang=ts&
 @ ./node_modules/taro-ui-vue/src/components/textarea/index.vue
 @ ./node_modules/taro-ui-vue/src/index.js
 @ ./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./node_modules/@tarojs/taro-loader/lib/raw.js!./src/pages/index/index.vue
 @ ./src/pages/index/index.vue,./node_modules/taro-ui-vue/src/utils/common.ts
Module build failed (from ./node_modules/babel-loader/lib/index.js):
SyntaxError: /Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/taro-ui-vue/src/utils/common.ts: Missing semicolon. (6:4)

  4 | const ENV = Taro.getEnv()
  5 |
> 6 | type ENVS = {
    |     ^
  7 |   isWEAPP: boolean
  8 |   isALIPAY: boolean
  9 |   isWEB: boolean
    at Parser._raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:134:45)
    at Parser.raiseWithData (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:129:17)
    at Parser.raise (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/error.js:78:17)
    at Parser.semicolon (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/util.js:138:10)
    at Parser.parseExpressionStatement (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:886:10)
    at Parser.parseStatementContent (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:374:19)
    at Parser.parseStatement (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:229:17)
    at Parser.parseBlockOrModuleBlockBody (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:961:25)
    at Parser.parseBlockBody (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:937:10)
    at Parser.parseProgram (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:116:10)
    at Parser.parseTopLevel (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/statement.js:101:25)
    at Parser.parse (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/parser/index.js:41:10)
    at parse (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/parser/src/index.js:26:26)
    at parser (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/core/lib/parser/index.js:52:34)
    at parser.next (<anonymous>)
    at normalizeFile (/Users/cuihonglei/workspace/2021/taro-demo/myApp/node_modules/@babel/core/lib/transformation/normalize-file.js:82:38)
 @ ./node_modules/taro-ui-vue/src/components/loading/index.vue?vue&type=script&lang=ts& (./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./node_modules/taro-ui-vue/src/components/loading/index.vue?vue&type=script&lang=ts&) 1:0-49 27:32-43 28:33-44
 @ ./node_modules/taro-ui-vue/src/components/loading/index.vue?vue&type=script&lang=ts&
 @ ./node_modules/taro-ui-vue/src/components/loading/index.vue
 @ ./node_modules/taro-ui-vue/src/index.js
 @ ./node_modules/babel-loader/lib!./node_modules/vue-loader/lib??vue-loader-options!./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./src/pages/index/index.vue?vue&type=script&lang=js&
 @ ./node_modules/@tarojs/taro-loader/lib/raw.js!./src/pages/index/index.vue
 @ ./src/pages/index/index.vue


(node:21564) UnhandledPromiseRejectionWarning: [object Array]
(node:21564) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 1)
(node:21564) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
