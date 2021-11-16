# Magic8Ball
import random

name = "Millicent"
question = "Will I put myself to bed tonight?"
answer = ""


random_number = random.randint(1,12)
#print(random_number)

if random_number == 1:
  answer = "Yes - definitely."
elif random_number == 2:
  answer = 'It is decidedly so.'
elif random_number == 3:
  answer ='Without a doubt.'
elif random_number == 4:
  answer = 'Reply hazy, try again.'
elif random_number == 5:
  answer = 'Ask again later.'
elif random_number == 6:
  answer = 'Better not tell you now.'
elif random_number == 7:
  answer = 'My sources say no.'
elif random_number == 8:
  answer = 'Outlook not so good.'
elif random_number == 9:
  answer = 'Very doubtful.'
elif random_number == 10:
  answer = 'Argh, fine!'
elif random_number == 11:
  answer = 'Daddy is a poo poo head!'
elif random_number == 12:
  answer = 'Sooo rude!!'
else:
  answer = "Error"

if question == "":
  print ("You have not asked a question. The Magic 8-Ball can't read minds!")
elif name == "":
  print ("Question: " + question)
else:
  print (name + " asks: " + question)


print ("Magic 8-Ball's answer: " + answer)

or
*/
let userName = 'Jamie';

userName ? console.log(`Hello, ${userName}!`): console.log('Hello!');

const userQuestion = 'Will I do well in this internship?';

console.log(`The user asked: ${userQuestion}`);

const randomNumber = Math.floor(Math.random() * 8);

let eightBall = '';

switch (randomNumber) {
  case 1:
    eightBall = 'It is certain';
    break;
  case 2:
    eightBall = 'It is decidely so';
    break;
  case 3:
    eightBall = 'Reply hazy try again';
    break;
  case 4:
    eightBall = 'Cannot predict now';
    break;
  case 5:
    eightBall = 'Do not count on it';
    break;
  case 6:
    eightBall = 'My sources say no';
    break;
  case 7:
    eightBall = 'Outlook not so good';
    break;
  case 8:
    eightBall = 'Signs point to yes';
    break;
  default:
    console.log('Your connection to this plane of understanding is currently unavailable. Please try again later.');
}

console.log(`The eight ball answered: ${eightBall}`)

*/
