MOUNTING // create component, first view
--------
constructor() => render() => componentDidMount()
// инициализацию компонентов, которые зависят от 
// внешних источников данных, лучше проводить в componentDidMount
// use for get data, work with DOM

UPDATES // can get update after mounting
-------
New Props 
            => componentDidUpdate(prevProps, prevState)
setState()

// fire after render()


UNMOUNTING // del component
----------
componentWillUnmount()
// before delete component, DOM still exists

ERROR // get error
-----
componentDidCatch(error, info)