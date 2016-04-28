# Middleware
## 1. What's middleware?
> Middleware lets you wrap the store’s dispatch method.

## 2. Why middleware?
[Redux middleware document](https://camsong.github.io/redux-in-chinese/docs/advanced/Middleware.html)

# Writing Middleware

[TODO 1-手動記錄](https://jsbin.com/taveti/1/edit)

[TODO 1-封裝Dispatch](https://jsbin.com/coqepi/edit?html,js,console,output)

[TODO 1-Monkeypatching Dispatch](https://jsbin.com/susafev/edit?js,console)

[TODO 1-隐藏 Monkeypatching](https://jsbin.com/cagako/edit?js,console)

[TODO 1-移除 Monkeypatching](https://jsbin.com/pilihu/edit?js,output)





[DEMO 2-thunk middleware](https://jsbin.com/towucac/1/edit?js,output)

# applyMiddleware

[source code](https://github.com/reactjs/redux/blob/master/src/applyMiddleware.js)
[source code demo](https://jsbin.com/sahomehefu/edit?js,output)

## nested function
  - currying
  - closure

## arrow function to rescue(simplify currying)
