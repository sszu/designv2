---
views:
    markdown:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/markdown

    byline:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/byline
---
Testsida - Markdown
======================

En testsida för att prova olika konstruktioner av Markdown och hur den samverkar med HTML.

Denna är sub-header (och bacon ipsum...)
----------------------
Spicy jalapeno flank aliqua dolore tempor in. Beef cow quis kevin non labore ea. Rump excepteur ipsum frankfurter eu chuck. Doner jowl beef eiusmod. Biltong eu cupidatat anim.

### Ytterligare sub-header, h3 denna gång

> Det här är blockcitat
>
> Och andra paragraph
>
> ###### h1-h6 fungerar även här

##### En annan inköpslista. h5 denna gång

1. Äpple
2. Banan
3. Päron

Testar länk via referens istället för inline
----------------------
Det finns många charter-arrangörer. Bland annat [Apollo][1], [Ving][2] och [TUI][3].

[1]: https://www.apollo.se  "Apollo"
[2]: https://www.ving.se    "Ving"
[3]: https://www.tui.se     "TUI"

Något blockcitat med hjälp av indentering
----------------------
    Här börjar citatet
        Indentera en gång till
            Och här slutar det

    Intressant
