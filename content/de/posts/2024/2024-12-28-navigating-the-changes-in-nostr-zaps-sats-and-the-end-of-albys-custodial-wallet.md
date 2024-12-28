---
date: 2024-12-28T15:26:13+03:00
lastmod: 2024-12-28T15:26:13+03:00
draft: false
title: 'Den Wandel in Nostr meistern'
description: "Zaps, Sats und das Ende von Albys Custodial Wallet"
lang: de
author: Ruben Storm
categories: ['post', 'blog']
tags: ['Nostr', 'Zaps', 'Satoshis', 'Alby', 'Lightning', 'Wallet', 'Dezentral', 'Protokol']
taxonomy: post
kind: page
showToc: false
TocOpen: false
hidemeta: false
comments: false
disableShare: false
disableHLJS: false # to enable|disable highlightjs - true|false
hideSummary: false
searchHidden: false # Hide or show in search
hideSitemap: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: false
UseHugoToc: true
cover:
    image: "/images/posts/2024/12/28/001.webp" # image path/url
    alt: "" # alt text
    caption: "" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
    hiddenInList: false # hide on list pages and home

---

Heute möchte ich ein technisches Thema ansprechen, das mir in letzter Zeit durch den Kopf geht. Wenn du mit **Nostr** vertraut bist, weißt du, dass es sich um ein dezentrales Protokoll handelt, das ein wenig an X (ehemals Twitter) erinnert. Anders als X ist Nostr jedoch keine Plattform, sondern ein Protokoll. Das bedeutet, es ist offen und flexibel und kann mit verschiedenen Clients genutzt werden.

In Nostr kannst du sowohl **Likes** als auch **Zaps** erhalten (kleine Bitcoin-Beträge, die über das Lightning-Netzwerk gesendet werden). Es gibt eine Vielzahl von Funktionen auf Nostr, wie etwa langförmige Inhalte über **NIP-23** oder **Pinstr**, ein Tool zum Teilen von Fotos. Heute möchte ich mich jedoch auf Zaps konzentrieren: das Senden und Empfangen von **Sats** (kurz für Satoshis, die kleinste Einheit von Bitcoin).

Für meine Transaktionen habe ich **Alby** genutzt, eine custodial Lightning-Wallet. Die Zaps werden über das Lightning-Netzwerk versendet, und ich habe **Nostr Wallet Connect (NWC)** verwendet, um meine Wallet mit meinem Nostr-Konto zu verknüpfen. Es war ein einfaches und effizientes System – bis jetzt.

## Das Problem

Alby hat kürzlich angekündigt, seinen custodial Wallet-Service einzustellen. Sie wechseln zum **Alby Hub**, einem non-custodial System, bei dem die Nutzer im Wesentlichen ihre eigene Lightning-Node betreiben müssen. Dieser Schritt entspricht zwar den Prinzipien der Dezentralisierung, bringt aber zusätzliche Kosten mit sich: etwa 12 US-Dollar pro Monat für das Hosting der Node.

Für jemanden wie mich, der keine nennenswerten Einnahmen aus Zaps auf Nostr erzielt, sind diese Kosten schwer zu rechtfertigen. Ich vermute, dass viele andere in der gleichen Situation sind und sich fragen, wie sie sich an diese Änderung anpassen können.

## Auf der Suche nach einer Lösung

Momentan suche ich noch nach einer praktikablen Alternative. Die Einfachheit und Zugänglichkeit von Albys custodial Wallet machte es zu einer großartigen Lösung für Nutzer wie mich, die über Nostr nicht viel verdienen. Es ist enttäuschend, dass dieser Service eingestellt wird, obwohl ich die finanziellen Herausforderungen verstehe, einen solchen Dienst aufrechtzuerhalten.

Derzeit wende ich mich an die Community. Gibt es andere Nostr-Nutzer, die effektive Lösungen für dieses Problem gefunden haben? Vielleicht hast du eine kostengünstige Möglichkeit entdeckt, deine Lightning-Wallet zu verwalten, oder eine Umgehung gefunden, die keine eigene Node erfordert. Falls ja, würde ich mich über deine Einblicke freuen.

## Abschließende Gedanken

Auch wenn ich über das Ende von Albys custodial Wallet traurig bin, bin ich zuversichtlich, dass die Kreativität der Nostr-Community zu neuen, benutzerfreundlichen Lösungen führen wird. In der Zwischenzeit werde ich weiterhin meine Optionen erkunden und meine Erkenntnisse teilen.

Wenn du Vorschläge oder Erfahrungen hast, teile den Link zu diesem Beitrag auf X (ehemals Twitter) oder poste ihn auf Nostr. Verlinke mich und füge deinen Kommentar hinzu, damit ich dein Feedback sehen kann. Lass uns gemeinsam eine Lösung finden!

### Twitter und Nostr

- **X (Twitter):** *rubenstorm*  
- **Nostr:** *npub1kt92nvl0xra26cz7tmhd3k3v3ltmfj5890kdc3qq9860h84tp76swuf0p0*  