![MUST-CTF2](https://github.com/3nhj0/MUST-CTF/assets/97040301/e1e6f38b-267f-4291-aef9-267a123c3499)


## Бодлого зохиогч нарын анхааралд!

Бүх флагны формат адилхан байх ёстой ба флаг формат нь **MUSTCTF{}** байна. 

- Бодлогоо оруулахдаа тус тусын category-д оруулах ба дараах зарчмыг баримтална. Үүнд: 

    Тухайн бодлогыг зохих category-д оруулах ба тухайн category-д бодлого тус бүрийн нэртэй folder байна. Мөн тухайн folder-т заавал "challenge" folder болон "challenge.yml" файл байна. "challenge" folder-т тухайн бодлогонд хэрэглэгдэх ( upload хийгдэх ) файлаа байршуулах ба "challenge.yml" файл дараах бүтэцтэй байна.

    ```
    name: 

      YOUR CHALLENGE NAME

    author: 

      YOUR NAME

    category: 

      "CATEGORY"
        CATEGORY MUST BE ONE OF crypto/forensics/misc/osint/programming/pwn/reverse/web

    description:

                   |-
      ADD DESCRIPTION

    value: 

      ENTER VALUE OF YOUR PROBLEM

    type:  

      standart/dynamic

    If it's dynamic -> :
    extra:
      initial: "ENTER INITIAL POINT OF YOUR PROBLEM"
      decay:  "DECREASING POINTS FROM SECOND SOLVER"
      minimum:  "ENTER THE MINIMUM SCORE FOR YOUR PROBLEM"

    flags:

      ADD FLAG OF YOUR PROBLEM, THAT MUST BE STARTS WITH "MUSTCTF{}"

    files:

      challenge/"PATH OF YOUR FILE"
      
    ```

Ойлгоход туслах, санаа авах байдлаар /round1/Cryptography дотор **color** даалгаврыг орууллаа. Challenge folder, "challenge.yml" болон standard эсвэл dynamic үед оруулах жишээ "sampleyml" folder дотор орууллаа. Жишээ болгож оруулсан файлтай заавал уншиж танилцана уу.

Форматын дагуу зөв оруулахад туслах байдлаар клубын хөтлөж байсан REPO-г хавсаргав. 
https://github.com/computer-communication-security-club/ctf-night/tree/halloween-special/challenges
