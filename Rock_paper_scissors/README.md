function playRound(playerSelection, computerSelection)
{

    while (computerSelection == "rock") { 
        if (playerSelection == "paper" )
        {
            console.log("You win, Paper beats Rock")
            
        } 
        else if (playerSelection == "scissors"){
            consle.log("You lose, Rock beats Scissors")
            
        }
        else if(playerSelection == "rock"){
            console.log("Its a tie")
            
        }
    }

    while (computerSelection == "paper") { 
        if (playerSelection == "scissors")
        {
            console.log("You win, scissors beats paper")
            
        } 
        else if (playerSelection == "rock"){
            console.log("You lose, Rock beats Scissors")
            
        }
        else if (playerSelection == "paper"){
            console.log("Its a tie")
            
        }
    }

    while (computerSelection == "scissors"){ 
        if (playerSelection == "rock" )
        {
            console.log("You win, Rock beats Scissors")
            
        } 
        else if (playerSelection == "paper"){
            console.log("You lose, Scissors beats Paper")
            
        }
        else if (playerSelection == "scissors"){
            console.log("Its a tie")
            
        }
    }
}

function game(){
playRound(playerSelection, computerSelection)
}
