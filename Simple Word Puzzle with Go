//Turkish people cCc

package main

import (
	"fmt"
	"strings"
)

func main() {
	var mainString string
	fmt.Print("Lütfen bir kelime girin: ")
	fmt.Scan(&mainString)

	var guessedWord string
	for i := 0; i < len(mainString); i++ {
		var guess string
		fmt.Printf("Tahmin ettiğiniz harf %d. deneme: ", i+1)
		fmt.Scan(&guess)

		if strings.HasPrefix(mainString[i:], guess) {
			guessedWord += guess
			fmt.Printf("Doğru! Tahmin edilen kelime: %s\n", guessedWord)
		} else {
			fmt.Println("Yanlış tahmin. Bir sonraki harfi deneyin.")
			i--
		}
	}

	fmt.Printf("Tebrikler! Kelimeyi buldunuz: %s\n", guessedWord)
}



//Global People


package main

import (
	"fmt"
	"strings"
)

func main() {
	var mainString string
	fmt.Print("Please enter a word:")
	fmt.Scan(&mainString)

	var guessedWord string
	for i := 0; i < len(mainString); i++ {
		var guess string
		fmt.Printf("Your guessed letter is %d. attempt: ", i+1)
		fmt.Scan(&guess)

		if strings.HasPrefix(mainString[i:], guess) {
			guessedWord += guess
			fmt.Printf("TRUE! Predicted word: %s\n", guessedWord)
		} else {
			fmt.Println("Wrong guess. Try the next letter.")
			i--
		}
	}

	fmt.Printf("Congratulations! You found the word: %s\n", guessedWord)
}
