## Skills required
Students will need to be able to:

 - Write nested conditional statements and/or write conditional statements with multiple criteria
 
## Advice
There are different ways to complete this challenge but encourage the use of nested conditional statements. They have access to the following Star Sign table.

| Date Range                      | Star Sign   |
| ------------------------------- | ----------- |
| March 21st     - April 19th     | Aries       |
| April 20th     - May 20th       | Taurus      |
| May 21st       - June 20th      | Gemini      |
| June 21st      - July 22nd      | Cancer      |
| July 23rd      - August 22nd    | Leo         |
| August 23rd    - September 22nd | Virgo       |
| September 23rd - October 22nd   | Libra       |
| October 23rd   - November 21st  | Scorpio     |
| November 22nd  - December 21st  | Sagittarius |
| December 22nd  - January 19th   | Capricorn   |
| January 20th   - February 18th  | Aquarius    |
| February 19th  - March 20th     | Pisces      |

## Solution

    day = int(input("Enter day"))
    month = int(input("Enter month"))

    if month == 3:
      if day >= 21:
        print("ARIES")
      else:
        print("PISCES")
    elif month == 4:
      if day >= 20:
        print("TAURUS")
      else:
        print("ARIES")
    elif month == 5:
      if day >= 21:
        print("GEMINI")
      else:
        print("TAURUS")
      
This is of course incomplete but gives you an idea of how to construct the program. This could be provided to less able students to complete.