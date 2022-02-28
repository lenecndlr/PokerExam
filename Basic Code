import java.util.Scanner;
public class Exam{
    public static void main(String[] args) {
        String[] SUITS = {
            "Clubs", "Diamonds", "Hearts", "Spades"
        };

        String[] RANKS = {
            "Ace", "2", "3", "4", "5", "6", "7", "8", "9", "10",
            "Jack", "Queen", "King",
        };
        // making the deck
        int n = SUITS.length * RANKS.length;
        String[] deck = new String[n];
        for (int i = 0; i < RANKS.length; i++) {
            for (int j = 0; j < SUITS.length; j++) {
                deck[SUITS.length*i + j] = RANKS[i] + " of " + SUITS[j];
            }
        }
        
        Scanner sc = new Scanner(System.in);
        int choice;
        System.out.println("1.) Draw");
        System.out.println("2.) Shuffle");
        System.out.println("3.) Restore");
        System.out.println("Pick what would you like to do with the cards");
        choice = sc.nextInt();
        
        switch(choice){
            case 1:
            //just printing out the deck which can be easily simplified.
            for (int i = 0; i < n; i++) {
                System.out.println(deck[i]);
            }
            break;
            case 2:
            //shuffling the deck but not the drawn cards
            for (int i = 0; i < n; i++) {
                int r = i + (int) (Math.random() * (n-i));
                String temp = deck[r];
                deck[r] = deck[i];
                deck[i] = temp;
            }
            break;
            case 3:
            //restoring the last N drawn cards on the bottom of the deck & if no number is provided, return all drawn cards.

            break;
        }
        sc.close();
    }

}
