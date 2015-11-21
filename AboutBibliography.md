# General mistakes in bibliography database #

The following are general mistakes in bibliography database (saved in thesis.bib).

**1. Each author must be separated by "and", don't use "," or ";" or "&"**

> wrong: Xuechun Li, Yuying Yang, Yongzhi Wang, Jun Bao, and Shunping Li <br>
<blockquote>wrong: Xuechun Li; Yuying Yang; Yongzhi Wang; Jun Bao ; Shunping Li <br>
wrong: Xuechun Li; Yuying Yang; Yongzhi Wang, Jun Bao & Shunping Li <br>
correct: Xuechun Li and Yuying Yang and Yongzhi Wang and Jun Bao and Shunping Li <br></blockquote>

<blockquote><img src='http://jkm.myconferences.org/jabref.png' /></blockquote>

<b>2. Comma "," character in the author field has a special meaning, but you do not know that</b>

<blockquote>You can write this: Xuechun Li and Yuying Yang and Yongzhi Wang and Jun Bao and Shunping Li <br>
with this: Li, Xuechun and Yang, Yuying and Yongzhi Wang and Jun Bao and Shunping Li <br>
You can write this: Waluyo Adi Siswanto and Badrul Omar <br>
with this: Siswanto, Waluyo Adi and Omar, Badrul <br>
You can write this : W. A. Siswanto and B. Omar <br>
with this: Siswanto, W.A and Omar, B. <br></blockquote>

<b>3. You are not using space after "." for author's initial. This will consider as one word</b>

<blockquote>wrong:  W.A. Siswanto and B. Omar <br>
why wrong: W.A without space after W. <br>
wrong: Wei Gan and R.H. Wagoner <br>
why wrong:  R.H will be considered as one word <br>
wrong: Wei Gan and RH Wagoner <br>
why wrong: RH will be considered as one name <br>
correct: Wei Gan and R. H. Wagoner <br>
why correct:  R. and H. will be considered as two names correctly <br></blockquote>

<b>4. Copying pages directly from internet source and paste it into the page field in jabref</b>

<blockquote>wrong: 1097�1113 <br>
why wrong: I copied from the internet the page information and pasted it to the page field in jabref. If you compile pdf, you will get an error. The character between the two pages is not plain ascii format.<br>
correct: 1097-1113<br>
why correct: using the "dash" character from the keyboard<br>
correct: 1097--1113<br>
why correct: using "dash" twice. This is also a correct way in Jabref.<br></blockquote>

<b>5. Special capital word in the title should be maintain as it appears in the original</b>

<blockquote>wrong: EasyFEM An object-oriented graphics interface finite element<br>
why wrong: In the reference list it will be changed to "Easyfem ...."<br>
correct: {EasyFEM} An object-oriented graphics interface finite element<br>
why correct: use a protection { }. Any word under { } will be written in the reference as it is <br>
<hr />
Back to<br>
<a href='https://code.google.com/p/uthm-thesis-lyx/w/list'>uthm-thesis-lyx Wiki List</a>.<br>
<hr />