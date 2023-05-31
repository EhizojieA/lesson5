Depending on where the r script is located the code will behave differently.

If placed outside of the ui/server elements then code will be ran once.

If placed within the brackets (argument) of the server function, then the code will be re-processed upon every new visitor.

If placed within the output$map <- renderPlot argument then the code will run everytime the user changes a widget that 
output$map depends on.

Refer to https://shiny.posit.co/r/getstarted/shiny-basics/lesson5/
