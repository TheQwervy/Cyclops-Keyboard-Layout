# Cyclops Keyboard Layout
A symmetrical, thumb-focused layout designed for phones.
<img width="1080" height="476" alt="Screenshot_20260628_201313_One UI Home" src="https://github.com/user-attachments/assets/61254859-0ac5-4940-87ae-59e69c9a4d11" />

### What?

Cyclops is an ortholinear keyboard layout designed for typing with two thumbs on mobile phones. It aims to have low same-thumb utilization and deprioritize the bottom corners of the screen.

In addition, Cyclops also aims to increase the size of each key by reducing the amount of keys per row.

A major characteristic of Cyclops is the centered function keys that are shared by each thumb, allowing better thumb alternations without the need to have large space bars or multiple shifts.

### Why?

After trying workman on my phone for a while and getting used to it, I noticed that I had some issues. For one, it prioritised using the home row. This is great if you're using all of your fingers, but when you're using thumbs, the outside keys require more effort to press. I feel that at least for myself, my thumbs tend to centre around an inverted triangle near the lower-centre of the screen.

The other part is on most keyboard layouts I find that the key density per row tends to make the keys relatively small which increases typing errors. I used to use the Typewise keyboard application. However, I wasn't a fan of the hexagonal layout as it is difficult to remember when touch-typing. I find an ortholinear layout to be much easier to remember the positioning of with my thumbs over a hexagonal layout. Additionally, I also feel that the layout I have created wastes less space by only requiring one spacebar instead of two.

### How?

I am using the custom layout setting in the FUTO keyboard application. (I'll comment the config for anyone to try)

I started the design process of Cyclops with the center function keys (the centered space being where it gets its name from). I then positioned the letters according to letter frequency. The most common letters I placed in the center upper portion of the keyboard, but not at the very top. I then started placing keys around them, fanning down towards the bottom corners in order of letter frequency. Additionally, similar to the Dvorak keyboard layout, I placed the vowels in the left hand and then tried to balance them on the right hand with common consonants such as T and N.

I used: https://norvig.com/mayzner.html and https://mdickens.me/typing/letter_frequency.html

As for the numbers and symbols, I placed the numbers in the left hand with 1 at the top and 0 at the bottom due to 1, 2, 3 being the most common numbers. I placed the symbols in the opposite order on the right hand side with the most common brackets being at the top and exclamation mark being near the other punctuation marks. I still roughly kept the order that you would see on a normal full sized keyboard from left to right for these.

I then made a pseudo version of Cyclops for the keyboard layout analyzer and ran text that I generated from chatgpt through it in order to simulate texting and sending emails. The most common typing things that I do on a phone.

I compared it with modified versions of the QWERTY and Workman layouts to simulate phone usage by restricting all the keys to only two fingers. After this, I did some light optimizations and compared it against some of the pre-existing texts from the KLA. Cyclops consistently scored better than both the modified versions of QWERTY and Workman by about two to three points over Workman in each text example.

I have not added the results because I am not satisfied with my own testing criteria nor my optimisations of this layout.

[Original post on reddit](https://www.reddit.com/r/KeyboardLayouts/comments/1ncf0nw/wip_cyclops_an_alternative_layout_for_phones/)
