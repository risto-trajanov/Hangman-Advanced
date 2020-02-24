# Hangman-Advanced
Zadacata Hangman so dopolnitelnite baranja.

Да се напише програма која со која ќе се игра играта бесилка.
Од тастатура најпрвин се внесува кој збор ќе се погодува, потоа колку обиди се
дозволени за погодување пред да те “обесат”. Откога ќе се внесат овие две вредности,
потребно е да се испечатат 30 празни редови во конзола за да ги скриеме овие податоци
од играчот.
Откога ќе се внесат овие две вредности, на играчот му се прикажува зборот што треба да
го внесе маскиран со * и му се печати колку обиди има преостанато за да го погоди
зборот.
Покрај маскираниот збор и обидите, дополнително треба да се печати и кои букви до тој
момент биле изиграни.
Од тастатура играчот внесува букви се додека не го погоди зборот или не е “обесен”.
Кога играчот ќе внесе некоја буква, таа треба да се прикаже во изиграните букви и
доколку постои во зборот да се “отворат” од маскираниот збор сите позиции каде се
среќава таа буква. Ако буквата не постои, на играчот му се намалуваат бројот на
преостанати обиди. Ако буквата била изиграна до сега, независно дали таа постои или не
во зборот, не му се одземаат обиди на играчот.
Кога ќе стигне играчот до крајот на играта:
- Ако го погодил зборот, се испишува: “YOU WON!”
- Ако е обесен: се испишува “You lost, the word was: (зборот откриен)”, каде (зборот
откриен) е зборот без звездички што го погодувал.
На секоја внесена буква на играчот му се пишуваат сите детали за играта како што е
опишано во пасусот погоре:
Маскираниот збор со *, колку обиди преостануваат и кои букви поминале до сега.

Проширување
1) Да се прошири играта така што независно дали е внесена голема или мала буква,
ако таа постои во зборот ќе може да се провери точно дали ја има во него
2) Да се прошири играта така што ќе може да се внесуваат реченици место еден
збор. Празното место во реченицата треба да е празно и кога се прикажува зборот
маскиран за погодување
3) Да се прошири задачата така што кога се внесува колку обиди се дозволени за
погодување, внесената вредност да мора да биде позитивен int. Се додека не се
внесе позитивен int, треба да се напише порака за грешка и вредноста повторно да
се внесе се додека не се внесе позитивен int.
