### If you wanna find some text in the component and return a error
`screen.getByText(<"text that you wanna find">)`

### If you wanna find some text in the component and return null to variable
`screen.queryByText(<"text that you wanna find">)` 

### If you wanna find some text in the component and return a Promise
`screen.findByText(<"text that you wanna find">)`

### If you wanna verify the class name of the component
`screen.toHaveClass(<"className  that you wanna find">)`

### If you wanna verify the class name of the component doesn't equal what you pass
`screen.not.toHaveClass(<"className  that you wanna find">)`
