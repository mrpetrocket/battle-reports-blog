---
title: "Gentlemen Do Not Read Each Other's Mail"
date: 2023-08-26
---
_Edited 8/27 for unclear explanation. Previous editor received 40 lashes at captain's mast._

The admiral ushers a young officer into the Duke's day cabin. Salutes are exchanged. The lieutenant is visibly nervous. As he should be. All men should respect their betters.

"This is the man you told me about?" the Duke asks, "The one who could listen to the enemy without knowing their cipher?" 

Admiral Daud nods. "It is because of this man's actions that we were able to act against the enemy yesterday," he explains, "Show our Duke how it is done."

At Daud's urging, the lieutenant steps forward.

Enemy radio traffic is encrypted with a secret cipher. The cipher consists of four numbers ranging from 1-32. Normally, our sailors must dive into burning enemy wrecks to recover these numbers from enemy code books. But there is good news for the fire-averse among us: this encryption presents at least two weaknesses that allow it to be decrypted *without* knowing cipher numbers beforehand.

I believe that the enemy's cipher is a "[substitution cipher](https://en.wikipedia.org/wiki/Substitution_cipher)". Every cleartext letter is replaced by an encrypted substitute. For example: "HELLO" might be replaced by "MKDDV".

The encryption is not as complete as the enemy thinks. The encrypted characters may be different, but (a) the length of the encrypted word remains the same as the cleartext word and (b) duplicate cleartext characters are represented by duplicate encrypted characters. If we see any encrypted word with a length or duplicate letter combination that matches a cleartext word we already know, we can use that word like a Rosetta stone to find the cipher that decrypts the entire message.

Here is the case in which I used this technique:

Today, we received an encrypted message with a very long recipient name. The length of the recipient name matched the length of a convoy name we have already learned, "FOMALHAUT". Furthermore, the recipient name had duplicate encrypted characters in the same positions as the duplicate "A"'s in FOMALHAUT. I moved the cipher dials one at a time until each set of letters in the recipient name matched up to FOMALHAUT. This done, we could now read the entire message in cleartext with the same cipher settings. Reading this message allowed us to launch a commerce raiding mission.
