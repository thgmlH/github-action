# github-action
Experiencing Service Operating Environment

1. Download Github Action Example .yml file and Test
2. 
  # Hello world docker action
  
  This action prints "Hello Github Action" or "Hello" + the name of a person to greet to the log.
  
  ## Inputs
  
  ## `who-to-greet`
  
  **Required** The name of the person to greet. Default `"Github Action"`.
  
  ## Outputs
  
  ## `time`
  
  The time we greeted you.
  
  ## Example usage
  
  uses: actions/hello-world-docker-action@v2
  with:
    who-to-greet: 'Mona the Octocat'

