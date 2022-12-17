# Goldman-Sachs-Crack-Leaked-Passsword-Database-Project

<h2>Password Controls and Security Policies</h2>

<h3>Overview</h3>

As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. To be successful at your job you often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

<h2>Project Objective</h2>

Your job is to crack as many passwords as possible with available tools (e.g. use Hashcat). Here are your Task instructions:

<ul>
  <li>Review the links provided in the resources section below to gain a background understanding of password cracking</li>
  <li>Try to crack the passwords provided in the 'password dump' file below using available tools
</li>
  <li>Assess the 5 questions in the task instructions below in relation to the passwords provided (type of hashing algorithm, level of protection, possible controls that could be implemented, password policy, changes in policy)</li>
  <li>Draft an email/memo briefly explaining your findings in relation to controls used by the organization and your proposed uplifts.</li>
</ul>

You must determine the following:

<ul>
  <li>What type of hashing algorithm was used to protect passwords?</li>

  <li>What level of protection does the mechanism offer for passwords?</li>

  <li>What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?</li>

  <li>What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?</li>

  <li>What would you change in the password policy to make breaking the passwords harder?</li>
</ul>

<h2>Project Report</h2>

After the conducted analysis we determined that the organization is using an outdated password algorithm which offers very little protection in the event of a password database leak. We also determined that the current password policy the organization is using is not aligned with industry best practices. As a result of the analysis I created and sent this document to Goldman Sachs which proposes the following uplifts to increase the overall level of password protection and help align their password policy with industry best practices.

<b>Dear Goldman Sachs

I am writing this email regarding the leaked password database to let you know about my findings and to let you know about my suggestions to improve your password policy and help keep your passwords secure in case of another breach.

After the conducted analysis it was determined that your organization uses the MD5 algorithm an outdated hashing algorithm which offers very little protection for hashing passwords. It was also determined that your current password policy is not aligned with the industries best practices allowing users to have short and noncomplex passwords. Seeing that you were using the MD5 hashing algorithm it was very easy to crack the leaked password hashes with hashcat and crackworkstation which is an online hash decoder. 

After cracking the passwords, we found that the organizations password policy has a minimum length of 6 characters for passwords and that there is no specific requirement for password creation. Users can use any combination of words and letters to create a password. As a result, I think the following controls could be implemented to increase the overall level of password protection and make cracking much harder in case of another database leak:

<ul>
<li>increase the password length this will increase the computational effort required to crack the passwords.</li>
<li>allow for all character types in a password and require at least one non-alphabetic character and usage of ASCII characters because every additional character increases the time it takes to crack a password exponentially and by adding numbers, symbols, upper and lowercase letters to the password it makes it very difficult to brute force. Thus, having a long, complex password is more secure.</li>
<li>Avoid common words and character combinations in your password.</li>
<li>regularly check current passwords to ensure that they have not been broken.</li>
  </ul>

Seeing that your current password policy is not aligned with the industries best practices things I would suggest to improve your password policy are:

<ul>
<li>Using a better hashing algorithm that provides a higher level of protection.</li>
<li>implementing salting and peppering to prevent usage of rainbow tables and make it harder to crack.</li>
<li>Having longer and stronger passwords which increases the time it takes to crack a password exponentially.</li>
<li>Train your users to follow these policies.</li>
</ul>

Kind Regards,

Aaron Alvarez</b>

<h2>Observations</h2>

In this section you can see what we observed when we ran the hashes through hashcat and crackworkstation. We could also see the output we got when we broke the hashes and finally we can see how easily the MD5 algorithm can be broken today using tools such as hashcat.

<b>Security Algorithms used:</b>

experthead:e10adc3949ba59abbe56e057f20f883e – MD5

interestec:25f9e794323b453885f5181f1b624d0b – MD5

ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 –MD5

reallychel:5f4dcc3b5aa765d61d8327deb882cf99 –MD5

simmson56:96e79218965eb72c92a549dd5a330112 – MD5

bookma:25d55ad283aa400af464c76d713c07ad – MD5 

popularkiya7:e99a18c428cb38d5f260853678922e03 – MD5

eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 – MD5

heroanhart:7c6a180b36896a0a8c02787eeafb0e4c – MD5

edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 – MD5

liveltekah:3f230640b78d7e71ac5514e57935eb69 – MD5

blikimore:917eb5e9d6d6bca820922a0c6f7cc28b – MD5

johnwick007:f6a0cb102c62879d397b12b62c092c06 – MD5

flamesbria2001:9b3b269ad0a208090309f091b3aba9db – MD5

oranolio:16ced47d3fc931483e24933665cded6d - MD5

spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e - MD5

moodie:8d763385e0476ae208f21bc63956f748 - MD5

nabox:defebde7b6ab6f24d5824682a16c3ae4 - MD5

bandalls:bdda5f03128bcbdfa78d8934529048cf - MD5

<b>Cracked Passwords:</b>

experthead:e10adc3949ba59abbe56e057f20f883e - 123456

interestec:25f9e794323b453885f5181f1b624d0b - 123456789

ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 - qwerty

reallychel:5f4dcc3b5aa765d61d8327deb882cf99 - password

simmson56:96e79218965eb72c92a549dd5a330112 - 111111

bookma:25d55ad283aa400af464c76d713c07ad - 12345678

popularkiya7:e99a18c428cb38d5f260853678922e03 - abc123

eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 - 1234567

heroanhart:7c6a180b36896a0a8c02787eeafb0e4c - password1

edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 - password!

liveltekah:3f230640b78d7e71ac5514e57935eb69 - qazxswPassword cracking explained (techniques described in 2013 still haven’t changed)

blikimore:917eb5e9d6d6bca820922a0c6f7cc28b - Pa$$word1

johnwick007:f6a0cb102c62879d397b12b62c092c06 - bluered

<h2>Resources</h2>

<a href="https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords">Password cracking explained (techniques described in 2013 still haven’t changed)</a>

<a href="https://en.wikipedia.org/wiki/Salt_(cryptography)">Password Salting</a>

<a href="https://en.wikipedia.org/wiki/Cryptographic_hash_function">Hash Functions</a>

<a href="https://en.wikipedia.org/wiki/Password_cracking#Software">Password Cracking Tools</a>

<a href="https://howsecureismypassword.net/">Password Strength Checker</a>
