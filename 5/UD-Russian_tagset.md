### A Russian tagset for UD 2.x

Updated: 17 Jan 2020   
Based on [UD guidelines](https://universaldependencies.org/guidelines.html)

## Parts of speech (UPOS)

|UPOS tag|Description (ru)|Description (en)|Examples|
|---|---|---|---|
|ADJ|прилагательное,порядковое числительное|adjective|новый, первый, должен, самый, сам, нужный|
|ADP|предлог|preposition|в, на, с, из-за, а-ля, типа|
|ADV|наречие, местоимение-наречие|adverb|так, уже, где, более, внимательно|
|AUX|вспомогательный грамматический показатель|auxiliary|быть, бы, б|
|CCONJ|сочинительный союз|coordinating conjunction|и, а, но, или, ни, то|
|DET|местоимение-прилагательное|determiner (adjectival pronoun)|наш, этот, весь, тот, его, каждый, какой|
|INTJ|междометие|iterjection|ах, о, а, та-да-дам, алло, ба|
|NOUN|существительное (нарицательное)|noun|год, человек, время, страна, дело|
|NUM|числительное|numeral|один, два, пять, много, несколько, 1, 10,5, 20.000|
|PART|частица|particle|не, и, же, только, даже, вот, ли, лишь, просто|
|PRON|местоимение-существительное|pronoun (nominal)|он, это, который, то, я, что, все|
|PROPN|существительное (собственное)|proper noun|Юрий, Гагарин, Ю. Москва, СССР, Земля, Каштанка, Beatles|
|PUNCT|пунктуация|punctuation mark|,, ., ", -, :, ), (, ?, !, …|
|SCONJ|подчинительный союз|subordinating conjunction|что, как, если, чтобы, когда, то, чем, хотя, поскольку, пока|
|SYM|символ|symbol|%, $, №, °, €, +, =, №№, 😉, ))|
|VERB|глагол (вкл. причастие, деепричастие)|verb|мочь, быть, стать, говорить, нет, нельзя, некуда, жаль|
|X|другое|foreign and non-words|of, and, the, in, de, mignews.com, @xxxxxx, http://xxxxxx, #ыыы|


## Grammatical features (FEAT)

| Cat=Feat | Description (ru) | Description (en) | UPOS | Examples|
|---|---|---|---|---|
| Abbr=Yes | аббревиатура | abbreviation | ADJ,DET,NOUN,NUM,PRON,PROPN,VERB | В., Евг., тел., за... |
| Animacy=Anim | одушевленное | animate | ADJ,DET,NOUN,NUM,PRON,PROPN,VERB* | человек, кошка, ученый, В., Путин, все(PRON), других |
| Animacy=Inan | неодушевленное | inanimate | ADJ,DET,NOUN,NUM,PRON,PROPN,VERB* | это, время, года, России, то, все(PRON), другие |
| Aspect=Imp | несовершенный вид | imperfective aspect | VERB | мочь, делать, любить, рождаться, говорить, становиться |
| Aspect=Perf | совершенный вид | perfective aspect | VERB | начать, сделать, разлюбить, родиться, сказать, стать |
| Case=Acc | винительный падеж | accusative case | ADJ,AUX*,DET,NOUN,NUM,PRON,PROPN,VERB* | время, его, это, их, что, все, то, себя, ее, раз |
| Case=Dat | дательный падеж | dative case | ADJ,AUX*,DET,NOUN,NUM,PRON,PROPN,VERB* | ему, мне, себе, моим, словам, мнению, всем |
| Case=Gen | родительный падеж | genitive case | ADJ,AUX*,DET,NOUN,NUM,PRON,PROPN,VERB* | года, того, лет, России, нас, всего, его, их |
| Case=Ins | творительный падеж | instrumental case | ADJ,AUX*,DET,NOUN,NUM,PRON,PROPN,VERB* | тем, образом, таким, собой, помощью, этим, ним, одним, ними, чем |
| Case=Loc | предложный падеж | locative case | ADJ,AUX*,DET,NOUN,NUM,PRON,PROPN,VERB* | том, этом, году, России, случае, результате, стране, самом, числе, мире |
| Case=Nom | именительный падеж | nominative case | ADJ,AUX*,DET,NOUN,NUM,PRON,PROPN,VERB | он, это, мы, Москва, великая |
| Case=Par | партитив (2-ой родит.) | partitive case | NOUN | разу, виду, народу, толку, чаю, ходу, голоду, сахару, дому, глазу |
| Case=Voc | звательный падеж | vocative case | NOUN,PROPN | господи, боже, Володь, Серег, дедуль |
| Degree=Cmp | сравнительная степень | comparative | ADJ,ADV | более, больше, менее, лучше, раньше, выше, дальше, чаще, позже, хуже |
| Degree=Pos | позитивная степень | positive | ADJ,ADV | синий, очень, глупо, так, например |
| Degree=Sup | превосходная степень | superlative | ADJ,ADV | важнейший, крупнейших, наиновейшие, высший, худший, внимательнейше |
| Foreign=Yes | иностранное слово | foreign word | PROPN,X | MBA, FIA, the, of, ButtKicker, and, PM, RoboCup, FOXP2, Weta |
| Gender=Fem | женский род | feminine gender | ADJ,AUX,DET,NOUN,NUM,PRON,PROPN,VERB | России, она, была, ее, этой, жизни, власти, страны, своей, эта |
| Gender=Masc | мужской род | masculine gender | ADJ,AUX,DET,NOUN,NUM,PRON,PROPN,VERB | он, был, его, года, лет, один, раз, ему |
| Gender=Neut | средний род | neuter gender | ADJ,AUX,DET,NOUN,NUM,PRON,PROPN,VERB | это, было, то, время, Бордо |
| Mood=Cnd | условное наклонение | conditional | AUX,SCONJ | чтобы, чтоб, бы, б |
| Mood=Imp | императив | imperative | AUX,VERB | см., давайте, будь, представьте, давай, дай, извините, иди, смотри, Вспомните |
| Mood=Ind | индикатив | indicative | AUX,VERB | было, был, есть, может, будет, были, была, нет, могут, будут |
| Number=Plur | множественное число | plural | ADJ,AUX,DET,NOUN,PRON,PROPN,VERB | мы, они, были, лет, Петушки, очки |
| Number=Sing | единственное число | singular | ADJ,AUX,DET,NOUN,PRON,PROPN,VERB | это, он, было, может, время, года, занят |
| Person=1 | 1-е лицо | first | AUX,PRON,VERB | я, мы, скажем, думаю, знаю, будем |
| Person=2 | 2-е лицо | second | AUX,PRON,VERB | вы, ты, вас, вам, тебя, тебе, вами, см., знаете, можешь |
| Person=3 | 3-е лицо | third | AUX,PRON,VERB | он, они, может, будет, есть |
| Polarity=Neg | отрицательная полярность | negative polarity | ADV,DET,PART,PRON,VERB("нет") | не, несмотря, ни, невзирая, нет, нет-нет, никто, никакой |
| Tense=Fut | будущее время | future | AUX,VERB | будет, скажем, станут, придется, сможет |
| Tense=Past | прошедшее время | past | AUX,VERB | было, стал, сказал, мог, заявил |
| Tense=Pres | настоящее время | present | AUX,VERB | есть, может, могут, является, говорит |
| Variant=Short | краткая форма | short form | ADJ,DET,VERB* | нужно, должны, известно, необходимо, должно |
| VerbForm=Conv | деепричастие | converb | AUX,VERB | говоря, начиная, учитывая, будучи, судя, исходя, состоявшись |
| VerbForm=Fin | финитная форма | finite | AUX,VERB | было, может, есть,  |
| VerbForm=Inf | инфинитив | infinitive | AUX,VERB | быть, сделать, сказать, делать, получиться |
| VerbForm=Part | причастие | participle | AUX,VERB | связано, связаны, сделано, окружающей, называемые, взявшийся |
| Voice=Act | активный залог | active | AUX,VERB | было, есть, может, будет, стать |
| Voice=Mid | средний залог | middle | VERB(reflexive) | является, удалось, становится, кажется, остается, приходится, находится |
| Voice=Pass | пассивный залог | passive | VERB* | связано, принято, связанных, понимаемый |

\* VERB*: participle forms

## SynTagRus tagset

| UPOS | Set of Vategories | Notes |
|---|---|---|
| ADJ | Animacy,Case,Degree,Gender,Number | if Case=Acc |
| ADJ | Animacy,Case,Degree,Number | if Number=Plur, Case=Acc, ordinal numerals |
| ADJ | Animacy,Case,Gender,Number |  |
| ADJ | Case,Degree,Gender,Number |  |
| ADJ | Case,Degree,Gender,Number,Variant |  |
| ADJ | Case,Degree,Number |  |
| ADJ | Case,Gender,Number |  |
| ADJ | Degree |  |
| ADJ | Degree,Gender,Number,Variant |  |
| ADJ | Degree,Number,Variant |  |
| ADJ | Foreign |  |
| ADJ | _ |  |
| ADP | _ |  |
| ADV | Degree |  |
| ADV | Polarity |  |
| AUX | Aspect,Case,Gender,Number,Tense,VerbForm,Voice |  |
| AUX | Aspect,Case,Number,Tense,VerbForm,Voice |  |
| AUX | Aspect,Gender,Mood,Number,Tense,VerbForm,Voice |  |
| AUX | Aspect,Mood,Number,Person,Tense,VerbForm,Voice |  |
| AUX | Aspect,Mood,Number,Person,VerbForm,Voice |  |
| AUX | Aspect,Mood,Number,Tense,VerbForm,Voice |  |
| AUX | Aspect,Tense,VerbForm,Voice |  |
| AUX | Aspect,VerbForm,Voice |  |
| AUX | _ |  |
| CCONJ | _ |  |
| DET | Animacy,Case,Degree,Gender,Number |  |
| DET | Animacy,Case,Degree,Number |  |
| DET | Animacy,Case,Gender,Number |  |
| DET | Case,Degree,Gender,Number |  |
| DET | Case,Degree,Number |  |
| DET | Case,Gender,Number |  |
| DET | Case,Number |  |
| DET | Gender,Number |  |
| DET | _ |  |
| INTJ | _ |  |
| NOUN | Animacy,Case,Gender,Number |  |
| NOUN | Animacy,Case,Number |  |
| NOUN | Animacy,Gender |  |
| NOUN | Case,Degree,Gender,Number |  |
| NOUN | _ |  |
| NUM | Animacy,Case |  |
| NUM | Animacy,Case,Gender |  |
| NUM | Case |  |
| NUM | Case,Gender |  |
| NUM | _ |  |
| PART | Mood |  |
| PART | Polarity |  |
| PART | _ |  |
| PRON | Animacy,Case,Gender,Number |  |
| PRON | Animacy,Case,Number |  |
| PRON | Animacy,Gender,Number |  |
| PRON | Case |  |
| PRON | Case,Gender,Number,Person |  |
| PRON | Case,Number,Person |  |
| PRON | Number,Person |  |
| PRON | _ |  |
| PROPN | Animacy,Case,Foreign,Gender,Number |  |
| PROPN | Animacy,Case,Gender |  |
| PROPN | Animacy,Case,Gender,Number |  |
| PROPN | Animacy,Case,Number |  |
| PROPN | Animacy,Gender |  |
| PROPN | Animacy,Gender,Number |  |
| PROPN | Case,Degree,Gender,Number |  |
| PROPN | Case,Degree,Number |  |
| PROPN | Foreign |  |
| PROPN | Number |  |
| PROPN | _ |  |
| PUNCT | _ |  |
| SCONJ | Mood |  |
| SCONJ | _ |  |
| SYM | _ |  |
| VERB | Animacy,Aspect,Case,Gender,Number,Tense,VerbForm,Voice |  |
| VERB | Animacy,Aspect,Case,Number,Tense,VerbForm,Voice |  |
| VERB | Aspect,Case,Gender,Number,Tense,VerbForm,Voice |  |
| VERB | Aspect,Case,Number,Tense,VerbForm,Voice |  |
| VERB | Aspect,Gender,Mood,Number,Tense,VerbForm,Voice |  |
| VERB | Aspect,Gender,Number,Tense,Variant,VerbForm,Voice |  |
| VERB | Aspect,Mood,Number,Person,Tense,VerbForm,Voice |  |
| VERB | Aspect,Mood,Number,Person,VerbForm,Voice |  |
| VERB | Aspect,Mood,Number,Tense,VerbForm,Voice |  |
| VERB | Aspect,Number,Tense,Variant,VerbForm,Voice |  |
| VERB | Aspect,Tense,VerbForm,Voice |  |
| VERB | Aspect,VerbForm,Voice |  |
| VERB | Voice |  |
| VERB | _ |  |
| X | Foreign |  |
| X | _ |  |
