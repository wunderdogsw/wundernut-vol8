# Wunderpähkinä #8 

Once again, our Wundernut proved to be very popular and we got over 50 entries. The problem proved to be rather easy to the contestants, as 34 of them reached the optimum solution of 21162 lines of text. Since the rules stated that “the shortest version of the book” would win, we decided to dig deeper and also took into account the length of the last line – as each of the 21162-line solutions had 80-character lines apart from the last line, the length of the last line would have to be included in the strict definition of “the shortest”.

This didn’t help much, as 22 of the afore-mentioned solutions also shared the shortest line length for the final row, 46 characters. So, the jury once again faced the difficult task of deciding which answer was most elegant – a subjective criterion, of course – in our opinion.

The winner of the 8th Wundernut, The Shortest Edition, is Stephen Sykes with his Ruby solution! We found his answer to be pleasant to read and rather smart and idiomatic, and lacking some obfuscating micro-optimizations found in some other answers giving a perfect result.

The jury would also like to give an honorable mention to Artti Jaakkola and his Java solution which had many of the winning answer’s good characteristics as well.

Some of the answers were blazing fast and we truly appreciate the effort the contestants had put into optimizing their solutions. However, as some of the answers were optimized only for particular environments, we couldn’t do a fair comparison between them on a single reference machine and thus will not declare a single fastest solution. But there were many solutions running in less than 0.5 seconds, written in many different languages.

Thank you to all the contestants for their entries!



A new edition of the Finnish literature classic novel “Alastalon Salissa” is planned to be made in traditional book form. The publisher would prefer it to be as compressed as possible, keeping the edit costs low and also saving the environment. To save as many trees as possible, the number of pages needs to be kept to the minimum. Some artistic liberties can be taken to meet this goal; the order of the words can be changed if it helps in compressing the book to use less pages. Because the publisher happens to be a perfectionist who does not compromise when it comes to art, all the words from the original book must be found in the new edition.

 

For making the compressed version, the words in the original novel are separated from each other on any whitespace. All punctuation marks in the words must be preserved. Separate punctuation marks are counted as one letter words.

Hereby, for instance this short story masterpiece:

"Kustaa-Jooseppi oli aina kokenut olevansa antilooppi. Niinpä hän nytkin laukkasi tuulispään lailla – kohti kukkeana siintävää merta."

forms 17 separate words:

"Kustaa-Jooseppi", "oli", "aina", "kokenut", "olevansa", "antilooppi.", "Niinpä", "hän", "nytkin", "laukkasi", "tuulispään", "lailla", "–", "kohti", "kukkeana", "siintävää", "merta."

 

In the new edition, the words need to be separated from each other with a space or a line break. With the help of mind-blowingly modern printing technique each row can fit a maximum of 80 characters, including spaces but excluding line breaks. Max 25 lines can be fit on one page. To keep the reading easy, the words cannot be conjugated, not even in the case of hyphens.

 

There’s no need for a separate name page in the beginning of the book or even for a header line in the beginning. The reader can directly dive into the actual story. The original name and publishing information is treated as all other words – meaning they can be in any part of the final edition since the order of the words could be changed.

 

Therefore, e.g. this made-up alphabetical poem:

"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa

bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb

cccccccccccccccccccccccccccccccccccccccccccccccccccccccccccc

dddddddddddddddddddddddddddddddddddddddd

eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee

fffffffffffffffffff

gggg

h"

can be shortened by using modern technology to just 4 rows, saving half of the original number of lines!

"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa h

bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb gggg

cccccccccccccccccccccccccccccccccccccccccccccccccccccccccccc fffffffffffffffffff

dddddddddddddddddddddddddddddddddddddddd eeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee"




## Checking your answer

Write your answer into a file (e.g. `answer_file.txt).

Then extract a validator binary for your platform from the validators-subdirectory and run it
with `./alastalo_validator answer_file.txt`.
