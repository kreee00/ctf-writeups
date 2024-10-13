
## Night Live at Indonesian

> Oeman is a nightlife maniac tourist in 2007 - 2010, he came back to Indonesia to enjoy the nightlife but the place was closed, what was the name of the place? And who was the person who closed the place?

We were given 5 images of unidentified nightclub(s) and a text file with a link to a Facebook account. The link was https://www.facebook.com/stacy.putri?mibextid=LQQJ4d . I go through the account and most of the pictures are about the nightclub. I can't find any clue.

Each images have watermark of "indonesiaclubbing.com". Went to the link and can't find any clue as well. At the end I took this image below

![5](https://github.com/user-attachments/assets/d838b4c8-266c-47e0-a995-1efa52fb2333)

and search using Yandex Image Search. I found this article about closure of a nightclub. It mentioned the name of politician that asked for the closure so I search him up on Wikipedia and finally got the flag

```
TCP1P{Basuki Tjahaja Purnama, 29 June 1966}
```


## The Investigator

> Help Jieyab found the newspaper. When was this newspaper published?
> 
> The flag name is date TCP1P{Date Month Year}

![PETRUS roeit Indonesische misdaad uit](https://github.com/user-attachments/assets/da028aa8-1486-4caa-a8d1-20bb9452d089)

Upon the success of previous challenge, I tried to use Yandex Image Search again but to no avail. Google Image Search also doesn't show any similar images. I realised that the newspaper is in Dutch language. So I ran a google search "dutch newspaper archive" then came across these two links below

1. https://libguides.ru.nl/news/delpher
2. https://www.delpher.nl/

The second link I need to use VPN to access. Then I just search the newspaper's main title "Links Frankrijk wil rechtse pers breken" and the original uncropped [article](https://www.delpher.nl/nl/kranten/view?query=Links+Frankrijk+wil+rechtse+pers+breken&coll=ddd&identifier=ddd:011205843:mpeg21:a0736&resultsidentifier=ddd:011205843:mpeg21:a0736&rowid=1) came up.

![Pasted image 20241012002303](https://github.com/user-attachments/assets/58ed6b40-4997-41da-9224-6de966774d28)

As you can see on left top there's the published date for the newspaper.

```
TCP1P{17 December 1983}
```


## The Pentagon

> A few days ago, I saw a funny post on a social media platform.
> 
> As far as I remember, there are five accounts that frequently post funny and random content.
> 
> I only remember two names: Udin Kurniawan Jaeger and Paijo Abdul Uchiha.
> 
> I recall that one of them uses a fake account. The humor in his posts is quite random, and I like it.
> 
> I want to know the real name of the person using that second account because I want to connect with him on his main account.
> 
> Please help me find his full real name.
> 
> The flag is the full name
> 
> Example: TCP1P{Kresna Yang Asli}

First thing I did, i google-ed both names given, "Udin Kurniawan Jaeger" and "Paijo Abdul Uchiha". Both showed a Reddit account but unfortunately both are suspended or deleted. So I use sherlock on both usernames `sherlock ud1nwanj4eger paij0uch1h4`. Turns out they got 9gag account. I went through ud1nwanj4eger's posts and stumbled upon ths one particular post with 14 comments

![Pasted image 20241012003315](https://github.com/user-attachments/assets/3ad8e9d3-3683-475a-915b-76dbac1cb306)

So I went through each comment and found a clue

![Pasted image 20241012003452](https://github.com/user-attachments/assets/ed6cc35c-b59f-47e8-9a0f-20a7109b1c9f)

At first I thought it was another 9gag posting so I go to this url https://9gag.com/u/DAJjWLRzVpw. But nothing came up. Then when I re-read the comment it says "that app with the photo logo", Instagram came to my mind. Thus, I just change the link to https://www.instagram.com/p/DAJjWLRzVpw/. It works! At the account bio it got mentioned "Second Account" which mentioned in challenge question. There's a link that direct you to a Discord channel. In the channel there's a bot with the same username, but when i try to chat it replied with

![Pasted image 20241012004004](https://github.com/user-attachments/assets/67698bb1-e314-4145-a9e3-7dce156f2902)

... Then I watch each posts on the Instagram account. One of the video, the audio sound distorted. I save the audio and play it using Audacity. Tried to play it at x0.5 but still sound like nonsense. So i try to reverse...and voila. The audio provide me with a password `tcp1p_th3p3nt490n_1s4w3s0m3` , i send to the chat with the bot and finally

![Pasted image 20241012004307](https://github.com/user-attachments/assets/ed813d32-22f1-4d61-8900-fb8a4def3010)

I opened the link and found the flag!

```
TCP1P{Slamet Setiawan Uzumaki}
```


## Journalist

> Oh no, help Jieyab to Found this video> 
> Link vidio : [https://drive.google.com/file/d/18zOX75x9gjITueQmwv0Bl9iffdQSYi5A/view?usp=sharing](https://drive.google.com/file/d/18zOX75x9gjITueQmwv0Bl9iffdQSYi5A/view?usp=sharing)
> Hint : Flag is time or date the video was uploaded
> *Pro tips
> Convert your time in WIB ( UTC+7) on the date metadata

I randomly screenshot one of the scene in the video and search using Google Image Search

![Pasted image 20241013002101](https://github.com/user-attachments/assets/31e68568-52c4-4919-9471-9e4f0e0866ab)

Found out the place is Shifa Hospital in Gaza City. So I open YouTube and type in this "shifa hospital gaza city jazeera". Watched all related videos to find the one that have the same reporter as the one in challenge video provided. Finally found the exact video >> https://www.youtube.com/watch?v=9dxQSvkow7Q

```
TCP1P{2 Apr 2024}
```
