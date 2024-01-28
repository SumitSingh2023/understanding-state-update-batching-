# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



# Code 1

In this code count is initialize by 0, and inside handleClick event function setCount is given to set the value of count, but after that count is being log but as in console the old value of count is showing this is happening because of ,when button is clicked handleClick function is being called and inside that function setCount is acting as Asynchronus so after consoling the value of count setCount is updating the value .This is also called React batching.


# code 2

In this code whenever this handleClick is being called then setCount is acting as asynchronus and not updating the value and insted of that it is printing the old value.

To update the new value ((prevCount)=>(prevCount+1)) is used 
