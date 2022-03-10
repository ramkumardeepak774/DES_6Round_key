# DES_6Round_key
At the start, we saw that there was a door with a panel nearby, We entered ‘read’ in order to read from the panel, but nothing appeared, so we went for another command and tried the ‘enter’ command to enter through the opening. After that we saw a lake in which we tried to jump, we came out, so we jumped again after that we tried to pull the magic wand, but unfortunately, we died. Now this time, we tried the following commands: ′ enter′− >′ jump′− >′ dive′− >′ back′ and then pulled the wand. After entering all these commands we went back to the 1st screen used the back′  command. Here we again tried to read from the panel but were unable to do so. We then went back to the spirit mentioned in level 3 and then entered into the chamber and waved the wand at the spirit to set it free. We  then went back to the   ﬁrst screen of level 3 and entered the commands in following order′ thrnxxtzy′− >′ read′− >′ 134721542097659029845273957′, 
After entering these commands we were able to clear the level. We then reached the 1st screen of level 4, used the read command, and got the screen where we can get the corresponding ciphertext for a  given plaintext.  As mentioned by the spirit the DES algorithm can be 4-round or 6-round, but we thought 4 rounds could be easy to break as compared to 6 rounds, so we thought to go first with 6 round DES, which finally gave us the solution. It also mentioned that 2 letters for 1 byte have been used, which meant that 1 letter consists of 4 bits. So we can have at most 16  letters.
On whispering "password", we got the encrypted password - "mkddpfgeshgpioghhejfjqsddmornqqf".
 On entering any other text on the next screen, we got the corresponding ciphertext. After getting the ciphertext we see the message displaying that the ciphertext is encrypted in DES and it can be any 4,6,10- round DES. Also, the spirit suggests that ‘he don’t remember which round DES it is but it is surely not the 10 round DES.’ So according to this information, it must be 4-round or 6-round DES. Now,4-round is easy to decrypt so let’s first try with the 6 round DES . We decrypt the 6-round DES by using the code given in des.txt. And if this try fails we can anyway go back to the 4-round DES.
 We have used the chosen-plaintext attack approach to break 6-round DES.Now, In this approach we send the plain text from the sender side and receives the encrypted text from the receiver side. And after this we make the pairwise analysis of the plaintext and corresponding ciphertext to get all the encrypted words. 
