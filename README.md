# -BMI-CALCULATOR-APP
```{r cars, echo = TRUE}
library(shiny)

# Define UI for application that calculate BMI
ui <- fluidPage(
    
    # Application title
    titlePanel("BMI CaLCULATOR APP"),
    
    # Sidebar with a slider input for Weight 
    sidebarLayout(
        sidebarPanel(
            sliderInput("Weight",label = "Weight",
                        
                        min = 20,
                        max = 70,
                        value = 100),
            sliderInput("Height",label = "Height",
                        min = 40,
                        max = 250,
                        value = 175,
                        
                        
            ),
            actionButton("Submitbutton","Submit",class =("btn-primary"))
            
        ),
        mainPanel(
            textOutput("contents"),
            # Results Table
        )
    )
)
```

## The server.R code is as follows

```{r,eval=FALSE,echo=TRUE}
# Define server logic required for BMI Calculator
library(shiny)


ui <- fluidPage(
)

server <- function(input, output, session) {
    
}

shinyApp(ui, server)

ui <- fluidPage(
    
)

server <- function(input, output, session) {
    
}

shinyApp(ui, server)

ui <- fluidPage(
    
)

server <- function(input,output) 
    dataset$input <-reactive({
        
    })
bmi <-input$Weight/ 
    (input$height/100)*input$height/100
bmi <- data.frame("bmi")
names(bmi) <- "bmi"
print(bmi)
#Status output box
outputOptions <- renderPrint
if(input$submition>0)
    isolate("calculation complete")
'else'
return("Server is ready to calculate")
# Prediction results table
output$tabledata <- renderDataTable()
if(input$submitbutton>0)
    isolate(datasetinput)
# Run the application 
shinyApp(ui = ui, server = server)
```

## Thank you
