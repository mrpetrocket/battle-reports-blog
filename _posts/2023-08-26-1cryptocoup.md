---
title: "Gentlemen Do Not Read Each Other's Mail"
date: 2023-08-26
---
The admiral ushers a young officer into the Duke's day cabin. Salutes are exchanged. The lieutenant is visibly nervous. As he should be. All men should respect their betters.
"This is the man you told me about?" the Duke asks, "The one who could listen to the enemy without knowing their cipher?" 
Admiral Daud nods. "It is because of this man's actions that we were able to act against the enemy yesterday," he explains, "Show our Duke how it is done."

At Daud's urging, the lieutenant steps forward.

Radio messages we intercept arrive in this form: `RECIPIENT= MESSAGE =SENDER` For example: `YOU= HELLO THERE =ME`.

The enemy encrypts their messages with a cipher that rotates on a schedule. The cipher consists of four numbers ranging from 1-32. Their encrypted messages have the same form as the unencrypted messages but with scrambled characters. For example: `YOU= HELLO THERE =ME` might look like `SLD= BMKKL VBMXM =UM`.

To decrypt a message, we turn four knobs from 1-32. The knobs' effect on the encrypted text is visible in real time.

Normally, our sailors must to dive into burning enemy wrecks to recover numbers from the cipher. Good news for the fire-averse: this encryption presents at least two weaknesses that allow it to be decrypted.

1. The position of spaces and the number of characters in each word are the same in the clear and encrypted text. If the length of a word is unique or matches a word we already know, twiddle the crypto knobs so that the suspicious word matches up with our clear text guess. I tried this with an unusually long recipient name I got from a previous cipher and was able to decrypt a message.

2. Each cleartext letter is always represented by a cleartext letter. I think this is called a (substitution cipher)[https://en.wikipedia.org/wiki/Substitution_cipher]. If a word has a strange number of duplicate letters, it has those same duplicate letters in cleartext. We can fiddle with the knobs as with (1) to match the suspicious word with our clear text guess.
