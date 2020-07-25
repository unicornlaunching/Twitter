document

.write

document.write

()

('')

('HTML')

document.write('<h1>Let’s get started!</h1>')


import * as React from 'react'
import * as ReactDOM from 'react-dom'

let helloWorld = <h1>Hello World!</h1>

ReactDOM.render(
    helloWorld,
    document.getElementById('react-root')
)
