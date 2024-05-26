Wie man ein Hacker wird
@Eric Steven Raymond
Thyrsus Unternehmen

    <esr@thyrsus.com>
    

Copyright © 2001 Eric S. Raymond

Versionsgeschichte
Revision 1.52	03. Januar 2020	esr
Go macht sich einen Platz als plausible Lernsprache, und verdrängt Java.
Revision 1.51	06. Oktober 2017	esr
Link zu "Dinge, die jeder Hacker einmal wusste". USB-Stick erwähnen Distributionen. Viele aktualisierte Übersetzungslinks.
Revision 1.50	19. Juli 2015	esr
Link zu "Let's Go Larval" hinzugefügt.
Revision 1.49	21. November 2014	esr
Link zu "How To Learn Hacking" hinzugefügt.
Revision 1.48	19. Juni 2014	esr
freshmeat/freecode ist leider tot.
Revision 1.47	20. Mai 2014	esr
Reparieren Sie verschiedene veraltete Links. Treten Sie einem Hackerspace bei!
Revision 1.46	25. September 2013	esr
Mikropatronage-Erklärung und Gittip-Link hinzufügen. Warum Sie mich nicht um Rat fragen sollten, wie Sie anfangen sollen.
Revision 1.45	12. Mai 2013	esr
Open Solaris ist es nicht, und Unity hat das Hündchen.
Revision 1.44	20. Mai 2012	esr
Die Kritik an Java wurde aktualisiert.
Revision 1.43	07. Februar 2011	esr
Python hat Perl 2010 in der Popularität überholt.
Revision 1.42	22 Okt 2010	esr
"Historische Notiz" hinzugefügt.
Revision 1.40	3. November 2008	esr
Link-Korrekturen.
Revision 1.39	14. August 2008	esr
Link-Korrekturen.
Revision 1.38	8. Januar 2008	esr
Verwerfen Sie Java als Sprache, die Sie früh lernen sollten.
Revision 1.37	4 Okt 2007	esr
Empfehlen Sie Ubuntu als Unix-Distribution für Neulinge.
Inhaltsverzeichnis

Warum dieses Dokument?
Was ist ein Hacker?
Die Hacker-Haltung
1. Die Welt ist voller faszinierender Probleme, die darauf warten, gelöst zu werden.
2. Kein Problem sollte jemals zweimal gelöst werden müssen.
3. Langeweile und Plackerei sind böse.
4. Freiheit ist gut.
5. Haltung ist kein Ersatz für Kompetenz.
Grundlegende Hacking-Fähigkeiten
1. Lernen Sie, wie man programmiert.
2. Holen Sie sich eines der Open-Source-Unixe und lernen Sie, es zu verwenden und auszuführen.
3. Lernen Sie, wie Sie das World Wide Web nutzen und HTML schreiben.
4. Wenn Sie kein funktionierendes Englisch haben, lernen Sie es.
Status in der Hackerkultur
1. Schreiben Sie Open-Source-Software
2. Helfen Sie beim Testen und Debuggen von Open-Source-Software
3. Veröffentlichen Sie nützliche Informationen
4. Helfen Sie, die Infrastruktur am Laufen zu halten
5. Dienen Sie der Hackerkultur selbst
Die Hacker/Nerd-Verbindung
Punkte für Stil
Historische Anmerkung: Hacking, Open Source, und Freie Software
Weitere Ressourcen
Häufig gestellte Fragen

Warum dieses Dokument?
Als Herausgeber des Jargon Datei und Autor einiger anderer bekannter Dokumente ähnlicher Art Von Natur aus bekomme ich oft E-Mail-Anfragen von begeisterten Netzwerk-Neulingen die Frage (im Grunde): "Wie kann ich lernen, ein magischer Hacker zu sein?". Zurück in 1996 bemerkte ich, dass es anscheinend keine anderen FAQs oder Web Dokumente, die sich mit dieser wichtigen Frage befassten, also begann ich mit diesem Eins. Viele Hacker halten es jetzt für endgültig, und ich Nehmen wir an, das bedeutet, dass es so ist. Trotzdem behaupte ich nicht, der Exklusive zu sein Autorität zu diesem Thema; Wenn Ihnen nicht gefällt, was Sie hier lesen, schreiben Sie Ihre eigene.

Wenn Sie einen Schnappschuss dieses Dokuments offline lesen, wird die Die aktuelle Version befindet sich unter http://catb.org/~esr/faqs/hacker-howto.html.

Hinweis: Es gibt eine Liste der häufig gestellten Fragen am Ende dieses Dokuments. Bitte lesen diese – zweimal – bevor sie mir Fragen dazu schickten Dokument.

Zahlreiche Übersetzungen dieses Dokuments sind verfügbar: Arabisch, Weißrussisch, Bulgarisch, Chinesisch, Tschechisch. Dänisch, Niederländisch, Estnisch, Französisch, Deutsch, Griechisch, Ungarisch, Italienisch, Hebräisch, Japanisch, Litauisch, Norwegisch, Persisch, Polnisch, Portugiesisch (Brasilianisch), Rumänisch, Spanisch, Türkisch, und Schwedisch. Beachten Sie, dass dieses Dokument gelegentlich geändert wird und sie möglicherweise nicht in unterschiedlichem Maße datieren.

Das Fünf-Punkte-in-neun-Quadrate-Diagramm, das dies schmückt Dokument wird als Gleiter bezeichnet. Es ist eine einfache Muster mit einigen überraschenden Eigenschaften in einer mathematischen Simulation namens Life, das Hacker seit vielen Jahren fasziniert. Ich denke, es macht eine gute visuelles Emblem dafür, wie Hacker sind – abstrakt, zunächst ein etwas mysteriös anmutend, aber ein Tor zu einer ganzen Welt mit einem komplizierte Logik für sich. Lesen Sie hier mehr über das Segelflugzeug-Emblem.

Wenn Sie dieses Dokument wertvoll finden, unterstützen Sie mich bitte auf Patreon oder SubscribeStar. Und Erwägen Sie auch, andere Hacker zu unterstützen, die Code erstellt haben, den Sie Nutzung und Wertschöpfung über Loadsharer. Mengen kleinen, aber kontinuierlichen Spenden summieren sich schnell und können die Menschen, die Ihnen ihre Arbeit geschenkt haben, um mehr zu schaffen Wert.

Was ist ein Hacker?
Der Jargon Die Datei enthält eine Reihe von Definitionen des Begriffs "Hacker", die meisten haben mit technischem Geschick und Freude am Lösen zu tun Probleme und die Überwindung von Grenzen. Wenn Sie jedoch wissen wollen, wie man ein Hacker wird, sind nur zwei wirklich einschlägig.

Es gibt eine Gemeinschaft, eine gemeinsame Kultur von erfahrenen Programmierern und Netzwerkassistenten, die ihre Geschichte über Jahrzehnte zurückverfolgen die ersten Time-Sharing-Minicomputer und das früheste ARPAnet Experimente. Die Mitglieder dieser Kultur haben den Begriff "Hacker". Hacker haben das Internet gebaut. Hacker machten die Unix-Betriebssystem, was es heute ist. Hacker machen die Welt Webarbeit. Wenn Sie Teil dieser Kultur sind, wenn Sie dazu beigetragen haben, Es und andere Leute darin wissen, wer Sie sind, und nennen Sie einen Hacker, Sie sind ein Hacker.

Die Hacker-Mentalität ist nicht auf diesen Software-Hacker beschränkt Kultur. Es gibt Leute, die die Hacker-Haltung auf andere anwenden Dinge wie Elektronik oder Musik – eigentlich findet man es bei das höchste Niveau jeder Wissenschaft oder Kunst. Software-Hacker erkennen diese verwandten Seelen anderswo und dürfen sie auch "Hacker" – und einige behaupten, dass der Hacker Die Natur ist wirklich unabhängig von dem jeweiligen Medium, mit dem der Hacker arbeitet in. Im weiteren Verlauf dieses Dokuments konzentrieren wir uns jedoch auf die Fähigkeiten und Einstellungen von Software-Hackern und die Traditionen der Kultur, die den Begriff "Hacker" hervorgebracht hat.

Es gibt noch eine andere Gruppe von Menschen, die sich laut selbst nennen Hacker, sind es aber nicht. Dies sind Menschen (hauptsächlich jugendliche Männer), die Genieße es, in Computer einzubrechen und das Telefon zu phreaken System. Echte Hacker nennen diese Leute "Cracker" und will nichts mit ihnen zu tun haben. Echte Hacker denken meistens, dass Cracker faul, verantwortungslos und nicht sehr klug, und dagegen zu protestieren, dass Sicherheit zu knacken macht Sie nicht mehr zu einem Hacker, als wenn Sie in der Lage sind, Autos zu verdrahten, macht Sie zu einem Automobilingenieur. Leider haben viele Journalisten und Schriftsteller wurden dazu verleitet, das Wort "Hacker", um Cracker zu beschreiben; Das irritiert echte Hacker Kein Ende.

Der grundlegende Unterschied ist folgender: Hacker bauen Dinge, Cracker Brechen Sie sie.

Wenn Sie ein Hacker sein wollen, lesen Sie weiter. Wenn du ein Cracker sein willst, Lesen Sie die alt.2600 Newsgroup und erhalten Sie Bereit, fünf bis zehn im Slammer zu machen, nachdem du herausgefunden hast, dass du nicht so gut bist Schlau, wie du denkst, dass du bist. Und das ist alles, worüber ich sagen werde Kekse.


Die Hacker-Haltung
1. Die Welt ist voller faszinierender Probleme, die darauf warten, gelöst zu werden.
2. Kein Problem sollte jemals zweimal gelöst werden müssen.
3. Langeweile und Plackerei sind böse.
4. Freiheit ist gut.
5. Haltung ist kein Ersatz für Kompetenz.
Hacker lösen Probleme und bauen Dinge, und sie glauben an Freiheit und freiwillige gegenseitige Hilfe. Um als Hacker akzeptiert zu werden, müssen Sie Verhalte dich so, als hättest du selbst diese Art von Einstellung. Und um Verhalten Sie sich so, als hätten Sie die Einstellung, Sie müssen wirklich an die Einstellung.

Aber wenn Sie die Hacker-Haltung nur als einen Weg betrachten Um Akzeptanz in der Kultur zu erlangen, werden Sie das Wesentliche verfehlen. Kleidsam die Art von Person, die glaubt, dass diese Dinge für Sie wichtig sind – um Ihnen beim Lernen zu helfen und Sie zu halten motiviert. Wie bei allen kreativen Künsten ist der effektivste Weg, um Ein Meister zu werden bedeutet, die Denkweise von Meistern nachzuahmen – nicht nur intellektuell, aber auch emotional.

Oder, wie es in dem folgenden modernen Zen-Gedicht heißt:


Um dem Weg zu folgen:
Schau auf den Meister,
folge dem Meister,
gehe mit dem Meister,
durchschaue den Meister,
werde der Meister.
Wenn Sie also ein Hacker sein wollen, wiederholen Sie die folgenden Dinge, bis Sie glauben ihnen:

1. Die Welt ist voller faszinierender Probleme, die darauf warten, gelöst zu werden.
Ein Hacker zu sein macht viel Spaß, aber es ist eine Art Spaß, der viel Aufwand. Die Anstrengung erfordert Motivation. Erfolgreiche Sportler erhalten ihre Motivation aus einer Art körperlicher Freude, ihre Körper performen, indem sie sich über ihre eigenen körperlichen Grenzen hinaus bewegen. Um ein Hacker zu sein, muss man einen grundlegenden Nervenkitzel beim Lösen bekommen Probleme zu lösen, Ihre Fähigkeiten zu schärfen und Ihre Intelligenz.

Wenn Sie nicht die Art von Person sind, die sich von Natur aus so fühlt, werden Sie man muss einer werden, um es als Hacker zu schaffen. Andernfalls werden Sie Finden Sie, dass Ihre Hacking-Energie durch Ablenkungen wie Sex, Geld und gesellschaftliche Anerkennung.

(Man muss auch eine Art Vertrauen in das eigene Lernen entwickeln Fähigkeit – ein Glaube, dass, auch wenn Sie vielleicht nicht alles wissen, was Sie ein Problem lösen müssen, wenn Sie nur einen Teil davon angehen und lernen Daraus lernst du genug, um das nächste Stück zu lösen – und so weiter, bis Sie fertig sind.)

2. Kein Problem sollte jemals zweimal gelöst werden müssen.
Kreative Gehirne sind eine wertvolle, begrenzte Ressource. Das sollten sie nicht sein verschwendet damit, das Rad neu zu erfinden, wenn es so viele faszinierende neue Probleme, die da draußen warten.

Um sich wie ein Hacker zu verhalten, muss man glauben, dass die Bedenkzeit von Andere Hacker sind wertvoll – so sehr, dass es fast eine moralische Pflicht ist damit Sie Informationen austauschen, Probleme lösen und dann die Lösungen weg, nur damit andere Hacker neue Probleme lösen können, anstatt sich ständig mit alten befassen zu müssen.

Beachten Sie jedoch, dass "kein Problem jemals gelöst werden muss zweimal." bedeutet nicht, dass Sie alle vorhandenen Lösungen heilig sind oder dass es nur eine richtige Lösung für jede gegebenes Problem. Oft lernen wir viel über das Problem, das wir nicht gelernt haben vorher wissen, indem Sie den ersten Schnitt an einer Lösung studieren. Es ist in Ordnung, und oft notwendig, um zu entscheiden, dass wir es besser machen können. Was nicht in Ordnung ist, ist künstliche technische, rechtliche oder institutionelle Barrieren (wie Closed-Source-Code), die verhindern, dass eine gute Lösung wiederverwendet wird und zwingen die Menschen, Räder neu zu erfinden.

(Sie müssen nicht glauben, dass Sie verpflichtet sind, Ihr gesamtes kreatives Produkt zu verschenken, obwohl die Hacker, die dies tun, sind diejenigen, die von anderen Hackern am meisten respektiert werden. Es entspricht den Werten von Hackern, genug davon zu verkaufen, um Sie im Spiel zu halten Essen und Miete und Computer. Es ist in Ordnung, Ihre Hacking-Fähigkeiten zu nutzen, um eine Familie zu ernähren oder sogar reich zu werden, solange man seine Loyalität zu deiner Kunst und deinen Hackerkollegen dabei.)

3. Langeweile und Plackerei sind böse.
Hacker (und kreative Menschen im Allgemeinen) sollten sich niemals langweilen oder sich an dummer, sich wiederholender Arbeit zu quälen, denn wenn das passiert, bedeutet, dass sie nicht das tun, was nur sie können – neue Probleme lösen. Diese Verschwendung schadet allen. Daher sind Langeweile und Plackerei nicht nur unangenehm, sondern tatsächlich böse.

Um sich wie ein Hacker zu verhalten, muss man das genug glauben, um es zu wollen Automatisieren Sie die Bohrbohrer so weit wie möglich, nicht nur für für sich selbst, sondern für alle anderen (insbesondere andere Hacker).

(Es gibt eine scheinbare Ausnahme. Hacker werden manchmal Dinge tun, die einem Beobachter repetitiv oder langweilig erscheinen mögen als Übung zur Bewusstseinsklärung oder um eine Fähigkeit zu erwerben oder eine bestimmte Art von Erfahrung, die man sonst nicht machen kann. Aber diese ist freiwillig – niemand, der denken kann, sollte jemals zu einem Situation, die sie langweilt.)

4. Freiheit ist gut.
Hacker sind von Natur aus antiautoritär. Jeder, der Ihnen geben kann Bestellungen können Sie davon abhalten, das Problem zu lösen, das Sie gerade haben fasziniert von – und angesichts der Art und Weise, wie autoritäre Köpfe arbeiten, im Allgemeinen einen entsetzlich dummen Grund dafür finden. Die autoritäre Haltung muss bekämpft werden, wo immer man sie findet, damit es erstickt Sie und andere Hacker.

(Das ist nicht dasselbe wie gegen jede Autorität zu kämpfen. Kinder müssen geführt und Kriminelle gezügelt. Ein Hacker kann zustimmen, einige zu akzeptieren Arten von Autorität, um etwas zu bekommen, das er mehr will als die Zeit, die er damit verbringt, Befehle zu befolgen. Aber das ist eine begrenzte, bewusste Gelegenheitskauf; Die Art von persönlicher Kapitulation, die Autoritäre wollen, ist nicht möglich Angebot.)

Autoritäre Menschen leben von Zensur und Geheimhaltung. Und sie der freiwilligen Zusammenarbeit und dem Informationsaustausch misstrauen – nur wie "Kooperation", die sie kontrollieren. So zu verhalten Wie ein Hacker muss man eine instinktive Feindseligkeit gegen Zensur, Geheimhaltung und die Anwendung von Gewalt oder Täuschung, um verantwortungsbewusste Erwachsene. Und man muss bereit sein, darauf zu reagieren Glaube.

5. Haltung ist kein Ersatz für Kompetenz.
Um ein Hacker zu sein, muss man einige dieser Einstellungen entwickeln. Aber Eine Einstellung allein zu bewältigen, wird Sie nicht zu einem Hacker machen, genauso wenig wie es wird Sie zu einem Spitzensportler oder einem Rockstar machen. Hacker werden erfordert Intelligenz, Übung, Hingabe und harte Arbeit.

Deshalb muss man lernen, der Einstellung und dem Respekt zu misstrauen Kompetenz jeder Art. Hacker lassen nicht zu, dass Poser ihre Zeit verschwenden, Aber sie verehren Kompetenz – besonders die Kompetenz im Hacken, aber Kompetenz in allem wird geschätzt. Kompetenz bei anspruchsvollen Fähigkeiten, die nur wenige beherrschen können, ist besonders gut, und Kompetenz bei anspruchsvollen Fähigkeiten die geistige Schärfe, Geschick und Konzentration erfordern, ist am besten.

Wenn du Kompetenz verehrst, wirst du sie gerne in dir selbst entwickeln – wird die harte Arbeit und Hingabe zu einer Art intensivem Spiel statt Plackerei. Diese Einstellung ist entscheidend, um ein Hacker.


Grundlegende Hacking-Fähigkeiten
1. Lernen Sie, wie man programmiert.
2. Holen Sie sich eines der Open-Source-Unixe und lernen Sie, es zu verwenden und auszuführen.
3. Lernen Sie, wie Sie das World Wide Web nutzen und HTML schreiben.
4. Wenn Sie kein funktionierendes Englisch haben, lernen Sie es.
Die Hacker-Einstellung ist von entscheidender Bedeutung, aber Fähigkeiten sind noch wichtiger. Haltung ist kein Ersatz für Kompetenz, und es gibt eine gewisse Grundhaltung Toolkit von Fähigkeiten, die Sie haben müssen, bevor ein Hacker träumt Sie einen zu nennen.

Dieses Toolkit ändert sich im Laufe der Zeit langsam, da die Technologie neue Fähigkeiten schafft und macht alte obsolet. Früher gehörte zum Beispiel die Programmierung in Maschinensprache und beinhaltete bis vor kurzem kein HTML. Aber Im Moment enthält es ziemlich eindeutig Folgendes:

1. Lernen Sie, wie man programmiert.
Dies ist natürlich die grundlegende Hacking-Fähigkeit. Wenn Sie dies nicht tun Computersprachen beherrschen, empfehle ich, mit Python zu beginnen. Es ist sauber gestaltet, gut dokumentiert und relativ anfängerfreundlich. Obwohl es eine gute Muttersprache ist, ist es nicht nur ein Spielzeug; Es ist sehr leistungsstark und flexibel und gut geeignet für große Projekte. Ich habe eine detailliertere Bewertung der Python. Gute Tutorials sind verfügbar bei Python Website; es gibt einen ausgezeichneten Drittanbieter bei Computer Science Kreise.

Früher habe ich Java als eine gute Sprache empfohlen, die man früh lernen sollte, aber das hier Kritik hat meine Meinung geändert (suche nach "Die Fallstricke der Java als erste Programmiersprache" enthalten). Ein Hacker kann nicht, wie sie es verheerend ausdrücken, "Problemlösungen angehen wie ein Klempner in einem Baumarkt"; Sie müssen wissen, was die Komponenten tun dies tatsächlich. Jetzt denke ich, dass es so ist wahrscheinlich ist es am besten, zuerst C und Lisp zu lernen, dann Java.

Hier gibt es vielleicht einen allgemeineren Punkt. Wenn eine Sprache dies auch tut Für Sie kann es gleichzeitig ein gutes Werkzeug für die Produktion und eine schlechte zum Lernen. Es sind nicht nur Sprachen, die dies haben Problem; Webanwendungs-Frameworks wie RubyOnRails, CakePHP, Django kann es zu einfach machen, zu einem oberflächlichen Verständnis zu gelangen, das werden Sie ohne Ressourcen zurücklassen, wenn Sie eine schwierige oder debuggen Sie einfach nur die Lösung für ein einfaches.

Eine bessere Alternative zu Java ist das Erlernen von Go. Diese relativ neue Sprache ist ziemlich einfach von Python zu wechseln, und wenn Sie es lernen, erhalten Sie eine ernsthafte Vorsprung auf den möglichen nächsten Schritt, nämlich das Erlernen von C. Eine der Unbekannten in den nächsten Jahren ist, inwieweit Go könnte C als Systemprogrammiersprache tatsächlich verdrängen. Es gibt eine mögliche Zukunft, in der dies über einen Großteil der traditionellen Bereich.

Wenn Sie ernsthaft programmieren, müssen Sie irgendwann C, die Kernsprache von Unix, lernen. C++ ist sehr eng mit C verwandt; Wenn Sie das eine kennen, wird es nicht schwierig sein, das andere zu lernen. Weder Sprache ist jedoch eine gute Sprache, die Sie als erstes lernen sollten. Und Je mehr Sie das Programmieren in C vermeiden können, desto produktiver Sie werden es sein.

C ist sehr effizient und schont die Betriebsmittel. Leider erhält C diese Effizienz, indem es von Ihnen verlangt, Führen Sie eine Menge Low-Level-Verwaltung von Ressourcen (wie Speicher) von Hand durch. All dieser Low-Level-Code ist komplex und fehleranfällig und saugt sich auf einen großen Teil Ihrer Zeit für das Debuggen. Mit den heutigen Maschinen als So mächtig sie auch sind, ist dies normalerweise ein schlechter Kompromiss – es ist klüger eine Sprache zu verwenden, die die Zeit der Maschine weniger effizient nutzt, aber Ihre Zeit viel effizienter. Daher Python.

Andere Sprachen, die für Hacker besonders wichtig sind, sind Perl und LISP. Perl ist es wert Lernen aus praktischen Gründen; Es ist sehr weit verbreitet für aktives Web Seiten und Systemadministration, so dass auch wenn Sie nie Perl schreiben Sie sollten lernen, es zu lesen. Viele Leute verwenden Perl auf die Art und Weise, wie ich schlagen vor, dass Sie Python verwenden sollten, um die C-Programmierung für Jobs zu vermeiden, die benötigen nicht die Maschineneffizienz von C. Sie müssen in der Lage sein, um ihren Code zu verstehen.

LISP ist es aus einem anderen Grund wert, gelernt zu werden – dem tiefgreifende Erleuchtungserfahrung, die ihr haben werdet, wenn ihr endlich es. Diese Erfahrung wird Sie zu einem besseren Programmierer für den Rest der Welt machen. Ihre Tage, auch wenn Sie LISP selbst nie oft verwenden. (Sie können Sammeln Sie relativ einfach erste Erfahrungen mit LISP, indem Sie schreiben und Ändern der Bearbeitungsmodi für den Emacs-Texteditor oder Script-Fu Plugins für GIMP.)

Es ist eigentlich am besten, alle fünf von Python, C/C++, Perl und LISP. Abgesehen davon, dass es sich um die wichtigsten Hacking-Sprachen handelt, Sie repräsentieren sehr unterschiedliche Programmieransätze, und jeder wird bilden Sie auf wertvolle Weise weiter. Go ist nicht ganz so weit, dass es zu den wichtigsten Hacking-Sprachen gezählt werden, aber scheint auf diesen Status zuzusteuern.

Aber seien Sie sich bewusst, dass Sie nicht das Qualifikationsniveau eines Hackers erreichen oder Selbst wenn man nur ein Programmierer ist, indem man einfach Sprachen anhäuft — müssen lernen, wie man über Programmierprobleme im Allgemeinen nachdenkt unabhängig von einer Sprache. Um ein echter Hacker zu sein, brauchen Sie an den Punkt zu gelangen, an dem Sie in wenigen Tagen eine neue Sprache lernen können, indem Sie Beziehen Sie das, was im Handbuch steht, auf das, was Sie bereits wissen. Das bedeutet, dass Sie sollten mehrere sehr unterschiedliche Sprachen lernen.

Ich kann keine vollständigen Anweisungen zum Programmieren geben Hier ist es eine komplexe Fähigkeit. Aber ich kann Ihnen sagen, dass Bücher und Kurse werden es nicht tun – viele, vielleicht die meisten der besten Hacker sind Autodidakten. Sie können Sprachfunktionen erlernen – Teile von Wissen – aus Büchern, sondern die Denkweise, die dieses Wissen ausmacht in lebendige Fertigkeiten können nur durch Übung und Lehrzeit erlernt werden. Was es tun wird, ist (a) Code zu lesen und (b) Code zu schreiben.

Peter Norvig, einer der Top-Hacker von Google und der Co-Autor des am weitesten verbreiteten Lehrbuchs über KI, hat einen ausgezeichneter Aufsatz mit dem Titel Teach Yourself Programming in Zehn Jahre. Sein "Rezept für Programmiererfolg" ist es wert sorgfältige Aufmerksamkeit.

Programmieren zu lernen ist wie zu lernen, gute natürliche Sprache zu schreiben. Der beste Weg, dies zu tun, ist, einige Dinge zu lesen, die von Meistern der Form, schreiben Sie einige Dinge selbst, lesen Sie viel mehr, schreiben Sie ein wenig mehr, viel mehr lesen, noch mehr schreiben ... und wiederholen Sie den Vorgang, bis Ihr Das Schreiben beginnt, die Art von Kraft und Ökonomie zu entwickeln, die man in Ihre Modelle.

Ich habe mehr über diesen Lernprozess in How To Learn Hacking zu sagen. Es ist ein Einfache Anleitung, aber keine einfache.

Früher war es schwierig, guten Code zum Lesen zu finden, weil es nur wenige gab große Programme, die im Quellcode für flügge gewordene Hacker zum Lesen und basteln. Dies hat sich dramatisch geändert; Open-Source-Software, Programmierwerkzeuge und Betriebssysteme (alle von Hackern entwickelt) jetzt weit verbreitet. Was mich zu unserem nächsten Thema bringt...

2. Holen Sie sich eines der Open-Source-Unixe und lernen Sie, es zu verwenden und auszuführen.
Ich gehe davon aus, dass Sie einen PC haben oder Zugang zu Eins. (Nehmen Sie sich einen Moment Zeit, um zu verstehen, wie viel das bedeutet. Der Hacker Die Kultur entwickelte sich ursprünglich, als Computer so teuer waren, dass Einzelpersonen konnten sie nicht besitzen.) Der wichtigste Schritt Neulinge können Hacker-Fähigkeiten erwerben, indem sie sich eine Kopie von Linux oder eines der BSD-Unixe, installieren Sie es auf einem persönlichen Rechner und führen Sie es aus.

Ja, es gibt noch andere Betriebssysteme auf der Welt Unix. Aber sie sind binär verteilt – man kann die Code, und Sie können ihn nicht ändern. Versuchen zu lernen, wie man auf einem Microsoft hackt Windows-Computer oder unter einem anderen Closed-Source-System ist wie der Versuch, um tanzen zu lernen, während man einen Gips trägt.

Unter Mac OS X ist es möglich, aber nur ein Teil des Systems ist geöffnet Quelle – Sie werden wahrscheinlich gegen viele Wände stoßen, und Sie müssen es sein Achten Sie darauf, nicht die schlechte Angewohnheit zu entwickeln, sich auf Apples proprietärer Code. Wenn Sie sich auf das Unix unter der Haube konzentrieren Sie können einige nützliche Dinge lernen.

Unix ist das Betriebssystem des Internets. Während Sie können lernen, das Internet zu benutzen, ohne Unix zu kennen, können Sie kein Internet-Hacker ohne Unix-Verständnis. Aus diesem Grund hat der Hacker Kultur ist heute ziemlich stark Unix-zentriert. (Das war nicht immer der Fall stimmt, und einige alte Hacker sind immer noch nicht glücklich darüber, aber die Die Symbiose zwischen Unix und dem Internet ist so stark geworden, dass selbst Microsofts Muskeln scheinen nicht in der Lage zu sein, es ernsthaft zu verbeulen.)

Also, bringen Sie ein Unix – ich mag Linux selbst, aber es gibt noch andere (und ja, Sie können sowohl Linux als auch Microsoft Windows auf demselben Computer). Lernen Sie es. Führen Sie es aus. Basteln Sie daran. Sprechen Sie damit mit dem Internet. Lesen Sie den Code. Ändern Sie den Code. Sie erhalten bessere Programmierwerkzeuge (einschließlich C, LISP, Python und Perl), von dem jedes Microsoft-Betriebssystem träumen kann, werden Sie Haben Sie Spaß, und Sie werden mehr Wissen aufsaugen, als Sie denken, Lernen, bis Sie als Meisterhacker darauf zurückblicken.

Weitere Informationen zum Erlernen von Unix finden Sie unter The Loginataka. Sie könnten auch mal einen Blick auf die Kunst der Unix-Programmierung.

Der Blog Let's Geh Larval! ist ein Fenster zum Lernprozess eines neuen Linux-Benutzer, den ich für ungewöhnlich klar und hilfsbereit halte. The post Wie I Learned Linux ist ein guter Ausgangspunkt.

Um ein Linux in die Hände zu bekommen, besuchen Sie die Linux Online!-Website; Sie können von dort herunterladen oder (bessere Idee) eine lokale Linux-Benutzergruppe finden, um helfen Ihnen bei der Installation.

In den ersten zehn Jahren dieses HOWTOs berichtete ich, dass aus Sicht eines neuen Benutzers sind alle Linux-Distributionen fast äquivalent. Aber in den Jahren 2006-2007 tauchte eine tatsächlich beste Wahl auf: Ubuntu. Während andere Distributionen ihren eigenen Stärken ist Ubuntu bei weitem der für Linux-Neulinge zugänglich. Hüten Sie sich jedoch vor den abscheulichen und nahezu unbrauchbare "Unity"-Desktop-Oberfläche, die Ubuntu als Zahlungsausfall ein paar Jahre später; die Xubuntu- oder Kubuntu-Varianten sind besser.

Hilfe und Ressourcen zu BSD Unix finden Sie unter www.bsd.org.

Eine gute Möglichkeit, Ihre Zehen ins Wasser zu tauchen, besteht darin, Linux-Fans rufen live an CD, eine Distribution, die vollständig von einer CD oder einem USB-Stick läuft ohne Ihre Festplatte modifizieren zu müssen. Dies kann langsam sein, weil CDs sind langsam, aber es ist eine Möglichkeit, einen Blick auf die Möglichkeiten zu werfen ohne etwas Drastisches tun zu müssen.

Ich habe eine Einführung in die Grundlagen geschrieben von Unix und dem Internet.

Früher habe ich davon abgeraten, Linux oder BSD als Solo-Projekt, wenn Sie ein Neuling sind. Heutzutage sind die Installateure gut genug, dass es möglich ist, es ganz alleine zu tun, selbst für eine Neuling. Trotzdem empfehle ich dennoch, Kontakt mit Ihrem lokalen Linux-Benutzergruppe und bittet um Hilfe. Es kann nicht schaden, und kann den Prozess erleichtern.

3. Lernen Sie, wie Sie das World Wide Web nutzen und HTML schreiben.
Die meisten Dinge, die die Hackerkultur aufgebaut hat, tun ihre Arbeit außer Sichtweite, half beim Betrieb von Fabriken, Büros und Universitäten ohne offensichtliche Auswirkungen auf das Leben von Nicht-Hackern. Das Web ist die Eine große Ausnahme, das riesige, glänzende Hackerspielzeug, von dem selbst Politiker zugeben, dass es die Welt verändert hat. Für Allein aus diesem Grund (und vielen anderen guten) müssen Sie lernen, wie man im Web arbeitet.

Das bedeutet nicht nur, zu lernen, wie man einen Browser steuert (jeder kann das), sondern zu lernen, wie man HTML schreibt, die Auszeichnungssprache des Webs. Wenn Sie nicht programmieren können, wird Ihnen das Schreiben von HTML einige beibringen mentale Gewohnheiten, die Ihnen beim Lernen helfen. Erstellen Sie also eine Homepage.

Aber nur eine Homepage zu haben, ist nicht annähernd gut genug, um machen Sie zu einem Hacker. Das Web ist voll von Homepages. Die meisten von ihnen sind sinnloser, inhaltsfreier Schlamm – sehr schick aussehender Schlamm, wohlgemerkt du, aber trotzdem schlammen (mehr dazu siehe Die HTML-Hölle Seite).

Um lohnenswert zu sein, muss Ihre Seite Inhalt haben – sie muss interessant und/oder nützlich sein an andere Hacker. Und das bringt uns zum nächsten Thema...

4. Wenn Sie kein funktionierendes Englisch haben, lernen Sie es.
Als Amerikaner und englischer Muttersprachler habe ich bisher gezögert, dies vorzuschlagen, damit es nicht als eine Art des Kulturimperialismus. Aber mehrere Muttersprachler anderer Sprachen haben mich dazu gedrängt, darauf hinzuweisen, dass Englisch die Sprache der Hackerkultur und des Internets, und dass Sie muss es wissen, um in der Hacker-Community zu funktionieren.

Um 1991 herum erfuhr ich, dass viele Hacker, die Englisch als eine zweite Sprache verwenden es in technischen Diskussionen, auch wenn sie eine Geburtszunge; wurde mir damals berichtet, dass Englisch eine reicheres technisches Vokabular als jede andere Sprache und ist daher einfach ein besseres Werkzeug für den Job. Aus ähnlichen Gründen können Übersetzungen von Fachbüchern, die in englischer Sprache verfasst sind, sind oft unbefriedigend (wenn sie werden überhaupt erledigt).

Linus Torvalds, ein Finne, kommentiert seinen Code auf Englisch (it anscheinend kam er nie auf die Idee, etwas anderes zu tun). Seine Sprachgewandtheit auf Englisch war ein wichtiger Faktor für seine Fähigkeit, eine weltweite Community von Entwicklern für Linux. Es ist ein Beispiel, das es wert ist, Folgende.

Ein englischer Muttersprachler zu sein, garantiert nicht, dass Sie Sprachkenntnisse, die gut genug sind, um als Hacker zu funktionieren. Wenn Ihr Schreiben ist halbgebildet, ungrammatikalisch und mit Rechtschreibfehlern gespickt, Viele Hacker (einschließlich mir) werden dazu neigen, Sie zu ignorieren. Während schlampig Schreiben bedeutet nicht ausnahmslos schlampiges Denken, wir haben im Allgemeinen fanden die Korrelation stark – und wir haben keine Verwendung für schlampige Denker. Wenn Sie noch nicht kompetent schreiben können, lernen Sie es.


Status in der Hackerkultur
1. Schreiben Sie Open-Source-Software
2. Helfen Sie beim Testen und Debuggen von Open-Source-Software
3. Veröffentlichen Sie nützliche Informationen
4. Helfen Sie, die Infrastruktur am Laufen zu halten
5. Dienen Sie der Hackerkultur selbst
Wie die meisten Kulturen ohne Geldwirtschaft läuft das Hackertum auf Ruf. Sie versuchen, interessante Probleme zu lösen, aber wie interessant sind, und ob Ihre Lösungen wirklich gut sind, ist etwas, das normalerweise nur Ihre technischen Kollegen oder Vorgesetzten sind Ausgestattet zum Urteilen.

Wenn Sie das Hacker-Spiel spielen, lernen Sie dementsprechend, Punkten Sie in erster Linie danach, was andere Hacker über Ihre Fähigkeiten denken (deshalb Sie sind nicht wirklich ein Hacker, bis andere Hacker Sie ständig anrufen eins). Diese Tatsache wird durch das Bild des Hackens als einsame Arbeit verschleiert; auch durch ein Hacker-kulturelles Tabu (das seit den späten 1990er Jahre, aber immer noch stark) gegen das Eingeständnis, dass das Ego oder die Validierung ist überhaupt an der Motivation beteiligt.

Konkret ist Hackertum das, was Anthropologen ein Geschenk nennen Kultur. Sie gewinnen Status und Ansehen darin, nicht durch Dominanz andere Menschen, noch dadurch, dass sie schön sind, noch dadurch, dass sie andere Dinge haben die Menschen wollen, sondern indem sie Dinge verschenken. Insbesondere durch Ihre Zeit, Ihre Kreativität und die Ergebnisse Ihrer Fertigkeit.

Es gibt im Grunde fünf Arten von Dingen, die Sie tun können, um respektiert zu werden hacker:

1. Schreiben Sie Open-Source-Software
Die erste (die zentralste und traditionellste) ist das Schreiben Programme, die andere Hacker für lustig oder nützlich halten, und geben dem Programmquellen an die gesamte Hackerkultur zu verwenden.

(Früher nannten wir diese Werke "freie Software", aber diese verwirrte zu viele Leute, die sich nicht genau sicher waren, was "kostenlos" ist soll bedeuten. Die meisten von uns bevorzugen mittlerweile den Begriff "Open-Source" Software).

Die am meisten verehrten Halbgötter des Hackertums sind Menschen, die große, leistungsfähige Programme, die einem weit verbreiteten Bedarf entsprachen und sie verschenkten, dass sie jetzt jeder benutzt.

Aber hier gibt es einen kleinen feinen historischen Punkt. Während Hacker haben immer zu den Open-Source-Entwicklern unter ihnen aufgeschaut als härtester Kern unserer Community, vor Mitte der 1990er Jahre die meisten Hacker Die meiste Zeit habe ich mit Closed Source gearbeitet. Das galt noch, als ich schrieb die erste Version dieses HOWTO im Jahr 1996; es brauchte die Mainstreaming von Open-Source-Software nach 1997, um die Dinge zu ändern. Heute sind "die Hacker-Community" und "Open-Source-Entwickler" zwei Beschreibungen für die im Wesentlichen gleiche Kultur und Bevölkerung – aber es sei daran erinnert, dass dies nicht immer der Fall war. Also. (Weitere Informationen hierzu finden Sie im Abschnitt "Historische Anmerkung: Hacking, Open Source, und Freie Software".)

2. Helfen Sie beim Testen und Debuggen von Open-Source-Software
Sie dienen auch denen, die Open-Source-Software stehen und debuggen. In In dieser unvollkommenen Welt werden wir unweigerlich den größten Teil unserer Software Entwicklungszeit in der Debugging-Phase. Deshalb ist jede Open-Source-Lösung Autoren, die nachdenken, werden Ihnen sagen, dass gute Beta-Tester (die wie man Symptome klar beschreibt, Probleme gut lokalisiert, tolerieren kann Bugs in einem Quickie-Release und sind bereit, ein paar einfache Diagnoseroutinen) sind ihr Gewicht in Rubinen wert. Sogar einer der Diese können den Unterschied zwischen einer Debugging-Phase ausmachen, die eine langwieriger, anstrengender Albtraum und einer, der nur ein heilsamer ist Ärgernis.

Wenn Sie ein Neuling sind, versuchen Sie, ein Programm in der Entwicklung zu finden, das Du bist interessiert und ein guter Beta-Tester. Es gibt eine natürliche von der Unterstützung beim Testen von Programmen zur Unterstützung beim Debuggen helfen, sie zu modifizieren. Auf diese Weise lernen Sie viel und generieren gutes Karma mit Menschen, die dir später helfen werden.

3. Veröffentlichen Sie nützliche Informationen
Eine weitere gute Sache ist es, nützliche und interessante Informationen in Webseiten oder Dokumente wie Listen mit häufig gestellten Fragen (FAQ) und erstellen Sie diese allgemein verfügbar.

Betreuer wichtiger technischer FAQs erhalten fast so viel Respekt wie Open-Source-Autoren.

4. Helfen Sie, die Infrastruktur am Laufen zu halten
Die Hackerkultur (und die technische Entwicklung der Internet) wird von Freiwilligen betrieben. Es gibt eine Menge notwendige, aber unglamouröse Arbeit, die getan werden muss, um sie zu erhalten Going — Mailinglisten verwalten, Newsgroups moderieren, Pflege großer Software-Archiv-Sites, Entwicklung von RFCs und anderen technischen Standards.

Leute, die so etwas gut machen, bekommen viel Respekt, weil Jeder weiß, dass diese Jobs enorme Zeitfresser sind und nicht so viel Spaß machen wie mit Code spielen. Sie zu tun, zeigt Hingabe.

5. Dienen Sie der Hackerkultur selbst
Schließlich können Sie die Kultur selbst bedienen und verbreiten (indem Sie Beispiel, eine genaue Einführung zu schreiben, wie man ein Hacker wird :-)). Dies ist nicht etwas, wozu Sie in der Lage sind, bis Sie und wurde für eine der ersten vier Dinge.

Die Hackerkultur hat keine Anführer, genau, aber sie hat Kulturhelden und Stammesälteste und Historiker und Sprecher. Wenn Sie lange genug in den Schützengräben waren, können Sie zu einem der diese. Vorsicht: Hacker misstrauen dem unverhohlenen Ego ihrer Stammesältesten, Es ist also gefährlich, sichtbar nach dieser Art von Ruhm zu greifen. Anstatt wenn man danach strebt, muss man sich irgendwie so positionieren, dass es und dann bescheiden und liebenswürdig mit Ihrem Status umgehen.


Die Hacker/Nerd-Verbindung
Entgegen dem landläufigen Mythos muss man kein Nerd sein, um ein Hacker. Es hilft jedoch, und viele Hacker sind tatsächlich Nerds. So etwas wie ein sozialer Außenseiter zu sein, hilft Ihnen, sich auf die wirklich wichtige Dinge, wie Denken und Hacken.

Aus diesem Grund haben viele Hacker das Label übernommen "Geek" als Abzeichen des Stolzes – es ist eine Art, ihre Unabhängigkeit von normalen gesellschaftlichen Erwartungen (sowie eine Vorliebe für andere Dinge wie Science-Fiction und Strategiespiele, die gehen oft damit einher, ein Hacker zu sein). Früher wurde der Begriff "Nerd" verwendet In den 1990er Jahren, als "Nerd" noch ein mildes Abwertungs- und "Geek" eine etwas härtere; irgendwann nach 2000 tauschten sie die Plätze, zumindest in der US-amerikanischen Populärkultur, und es gibt jetzt sogar eine signifikante Geek-Pride-Kultur unter Leuten, die keine Technikfreaks sind.

Wenn Sie es schaffen, sich genug auf das Hacken zu konzentrieren, um gut darin zu sein und trotzdem ein Leben haben, das ist in Ordnung. Das ist heute viel einfacher als es war, als ich in den 1970er Jahren ein Neuling war; Mainstream-Kultur ist viel jetzt freundlicher zu Techno-Nerds. Es gibt sogar eine wachsende Zahl von Menschen, die erkennen, dass Hacker oft hochwertige Liebhaber und Ehegattenmaterial.

Wenn Sie sich zum Hacken hingezogen fühlen, weil Sie kein Leben haben, das ist auch in Ordnung – zumindest werden Sie keine Konzentrationsprobleme haben. Vielleicht Sie werden später ein Leben bekommen.


Punkte für Stil
Auch hier gilt: Um ein Hacker zu sein, muss man sich in die Hacker-Mentalität versetzen. Dort sind einige Dinge, die Sie tun können, wenn Sie nicht an einem Computer sitzen, die Hilfe. Sie sind kein Ersatz für Hacking (nichts ist es), aber viele Hacker machen sie und haben das Gefühl, dass sie auf eine grundlegende Weise miteinander verbunden sind mit der Essenz des Hackens.

Lernen Sie, Ihre Muttersprache gut zu schreiben. Obwohl Es ist ein weit verbreitetes Klischee, dass Programmierer nicht schreiben können, ein überraschend viele Hacker (darunter die versiertesten die, die ich kenne) sind sehr fähige Schriftsteller.

Lesen Sie Science-Fiction. Zu Science-Fiction Conventions (eine gute Möglichkeit, Hacker und Proto-Hacker zu treffen).

Treten Sie einem Hackerspace bei und machen Sie Dinge (eine weitere gute Möglichkeit, Hacker und Proto-Hacker zu treffen).

Trainieren Sie in einer Kampfsportform. Die Art der mentalen Disziplin, die für Kampfkünste erforderlich ist, scheint in Wichtige Wege zu dem, was Hacker tun. Die beliebtesten Formen unter Hacker sind definitiv asiatische Künste mit leeren Händen wie Tae Kwon Do, verschiedene Formen von Karate, Kung Fu, Aikido oder Ju Jitsu. Westlich Fechten und asiatische Schwertkünste haben ebenfalls sichtbare Anhänger. In Orte, an denen es legal ist, hat das Pistolenschießen zugenommen Popularität seit den späten 1990er Jahren. Die hackerhaftesten Kampfkünste sind solche, die mentale Disziplin, entspanntes Bewusstsein, und präzise Kontrolle, anstatt rohe Kraft, Athletik oder Physis Zähigkeit.

Studieren Sie eine tatsächliche Meditationsdisziplin. Die Staude Favorit unter Hackern ist Zen (wichtig ist, dass es möglich ist, vom Zen profitieren, ohne eine Religion zu erwerben oder abzulegen Sie haben es bereits). Andere Stile können auch funktionieren, aber seien Sie vorsichtig eine zu wählen, bei der man nicht verrückt glauben muss Dinge.

Entwickeln Sie ein analytisches Ohr für Musik. Lernen Sie besondere Arten von Musik schätzen. Lernen Sie, etwas Musical zu spielen Instrument gut, oder wie man singt.

Entwickeln Sie Ihre Wertschätzung für Wortspiele und Wortspiel.

Je mehr dieser Dinge Sie bereits tun, desto wahrscheinlicher ist es, dass Sie sind natürliches Hackermaterial. Warum gerade diese Dinge nicht völlig klar, aber sie sind mit einer Mischung aus Links- und Fähigkeiten der rechten Gehirnhälfte, die wichtig zu sein scheinen; Hacker müssen in der Lage sein, sowohl logisch zu argumentieren als auch aus dem Offensichtlichen herauszutreten Logik eines Problems im Handumdrehen.

Arbeite so intensiv, wie du spielst, und spiele so intensiv, wie du arbeitest. Für echte Hacker sind die Grenzen zwischen "Spiel", "Arbeit", "Wissenschaft" und "Kunst" neigen dazu, zu verschwinden oder zu einem kreativen Munterkeit. Geben Sie sich auch nicht mit einem engen Spektrum an Fähigkeiten zufrieden. Obwohl sich die meisten Hacker selbst als Programmierer bezeichnen, sind sie sehr wahrscheinlich in mehreren verwandten Fertigkeiten mehr als kompetent zu sein — System Administration, Webdesign und PC-Hardware-Fehlerbehebung sind üblich einsen. Ein Hacker, der ein Systemadministrator ist, hingegen Wahrscheinlich ziemlich geschickt in Skriptprogrammierung und Webdesign. Hacker machen keine halben Sachen; wenn sie überhaupt in eine Fähigkeit investieren, sie neigen dazu, sehr gut darin zu werden.

Zum Schluss noch ein paar Dinge, die Sie nicht tun.

Verwenden Sie keine alberne, grandiose Benutzer-ID oder einen Bildschirmnamen.

Lassen Sie sich nicht auf Flame Wars im Usenet (oder anderswo) ein. sonst).

Nennen Sie sich nicht "Cyberpunk" und verschwenden Sie keine Ihre Zeit für jeden, der es tut.

Posten oder mailen Sie keine Schreibweise, die voller Rechtschreibung ist Fehler und schlechte Grammatik.

Der einzige Ruf, den Sie sich bei all diesen Dingen verdienen werden, ist der eines Dussel. Hacker haben ein langes Gedächtnis – es kann Jahre dauern, bis Sie leben deine frühen Fehler sind so weit heruntergekommen, dass du akzeptiert wirst.

Das Problem mit Bildschirmnamen oder Handles verdient etwas Verstärkung. Das Verbergen Ihrer Identität hinter einem Griff ist ein Jugendlicher und albernes Verhalten, das für Cracker, Warez D00DZ und andere charakteristisch ist niedere Lebensformen. Hacker tun dies nicht; sie sind stolz auf das, was sie tun und wollen, dass es mit ihren richtigen Namen in Verbindung gebracht wird. Wenn Sie also einen Griff haben, lassen Sie ihn fallen. In der Hackerkultur wird es nur Markiere dich als Verlierer.


Historische Anmerkung: Hacking, Open Source, und Freie Software
Als ich diese Anleitung Ende 1996 schrieb, waren einige der Die Bedingungen um ihn herum waren ganz anders als heute. Ein paar Worte zu diesen Änderungen mögen helfen, die Dinge für die Menschen zu klären die über das Verhältnis von Open Source, Free Software und Linux für die Hacker-Community. Wenn Sie nicht neugierig sind können Sie direkt zu den FAQ und der Bibliographie von hier.

Das Hacker-Ethos und die Community, wie ich es hier schon lange beschrieben habe vor dem Aufkommen von Linux nach 1990; Ich habe mich zum ersten Mal engagiert mit ihm um 1976, und seine Wurzeln lassen sich leicht bis in die Anfang der 1960er Jahre. Aber vor Linux wurde das meiste Hacken auf beiden Seiten durchgeführt proprietäre Betriebssysteme oder eine Handvoll quasi-experimenteller selbst entwickelte Systeme wie das ITS des MIT, die nie außerhalb von ihre ursprünglichen akademischen Nischen. Während es früher einige gegeben hatte (vor Linux) versuchten, diese Situation zu ändern, waren ihre Auswirkungen am besten sehr marginal und auf Gemeinschaften von engagierten wahren Gläubige, die selbst innerhalb der Hacker-Community winzige Minderheiten waren, geschweige denn in Bezug auf die größere Welt der Software in Allgemein.

Was heute als "Open Source" bezeichnet wird, reicht bis zum Hacker zurück Gemeinschaft tut es, aber bis 1985 war es eine unbenannte Volkspraxis als eine bewusste Bewegung mit Theorien und Manifesten, die damit verbunden sind. Diese Vorgeschichte endete, als 1985 der Erzhacker Richard Stallman ("RMS") versuchte, ihm einen Namen zu geben – "freie Software". Aber seine Handlung des Benennens war auch ein Akt des Anspruchs; Er hängte ideologisches Gepäck an auf das Etikett "Freie Software", das ein Großteil der bestehenden Hacker Gemeinschaft nie akzeptiert. Infolgedessen wurde das Label "Freie Software" von einer beträchtlichen Minderheit der Hacker-Community lautstark abgelehnt (insbesondere bei denen, die mit BSD Unix verbunden sind) und mit ernsthafte, aber stillschweigende Vorbehalte der Mehrheit der übrigen (einschließlich mir).

Trotz dieser Vorbehalte ist der Anspruch von RMS, die Hacker-Community unter dem Banner "Freie Software" Mitte der 1990er Jahre. Es wurde erst durch den Aufstieg von Linux ernsthaft in Frage gestellt. Linux gab der Open-Source-Entwicklung ein natürliches Zuhause. Viele Projekte veröffentlicht unter Bedingungen, die wir jetzt als Open-Source-migriert von proprietäre Unixe zu Linux. Die Community rund um Linux wuchs explosiv und viel größer und heterogener als die Prä-Linux-Hacker-Kultur. RMS versuchte entschlossen, alle zu vereinnahmen diese Aktivität in seine "Freie-Software"-Bewegung, wurde aber durch sowohl die explodierende Vielfalt der Linux-Community als auch der Öffentlichkeit Skepsis gegenüber seinem Gründer, Linus Torvalds. Torvalds verwendete weiterhin den Begriff "Freie Software" mangels Alternative, aber öffentlich das ideologische Gepäck der RMS zurückgewiesen. Viele jüngere Hacker folgten Anzug.

Als ich 1996 zum ersten Mal dieses Hacker-HOWTO veröffentlichte, wurde der Hacker -Community schnell um Linux und eine Handvoll anderer Open-Source-Betriebssysteme (insbesondere solche, die von BSD Unix). Gemeinschaftliche Erinnerung an die Tatsache, dass die meisten von uns Jahrzehnte damit verbracht hatten, Entwicklung von Closed-Source-Software auf Closed-Source-Betriebssystemen noch nicht zu verblassen begonnen hatte, aber diese Tatsache schien bereits wie ein Teil einer toten Vergangenheit; Hacker definierten zunehmend sich selbst als Hacker durch ihre Anhänge an Open-Source-Projekte wie Linux oder Apache.

Der Begriff "Open Source" war jedoch noch nicht aufgetaucht; es würde nicht vor Anfang 1998. Als dies der Fall war, wurde der größte Teil der Hackergemeinde sie innerhalb der folgenden sechs Monate angenommen hat; Ausnahmen waren ein Minderheit, die ideologisch mit dem Begriff "Freie Software" verbunden ist. Seit 1998 und insbesondere nach etwa 2003 die Identifizierung von "Hacking" mit "Open-Source- (und Freie-Software-) Entwicklung" extrem nah. Heute hat es wenig Sinn, zu versuchen, zwischen diesen Kategorien unterscheiden, und es scheint unwahrscheinlich, dass Wandel in der Zukunft.

Es lohnt sich jedoch, sich daran zu erinnern, dass dies nicht immer so war.


Weitere Ressourcen
Paul Graham hat einen Essay mit dem Titel Great Hackers geschrieben, und ein anderer über Undergraduation, worin er viel Weisheit spricht.

Jüngere Hacker könnten Things Every finden Hacker Once Knew interessant und nützlich.

Ich habe auch A geschrieben Kurze Geschichte des Hackertums.

Ich habe eine Abhandlung geschrieben, The Cathedral und der Basar, der viel darüber erklärt, wie die Linux und Open-Source-Kulturen funktionieren. Ich habe dieses Thema sogar angesprochen direkter in der Fortsetzung Homesteading die Noosphäre.

Rick Moen hat ein ausgezeichnetes Dokument darüber geschrieben, wie man eine Linux-Benutzergruppe.

Rick Moen und ich haben an einem weiteren Dokument über How Kluge Fragen zu stellen. Dies wird Ihnen helfen, Hilfe zu suchen auf eine Weise, die es wahrscheinlicher macht, dass Sie es tatsächlich bekommen.

Wenn Sie eine Einweisung in die Grundlagen benötigen, wie PCs, Unix und das Internet funktionieren, siehe The Unix and Internet Fundamentals HOWTO.

Wenn Sie Software veröffentlichen oder Patches für Software schreiben, versuchen Sie, Befolgen Sie die Richtlinien im Software Release Practice HOWTO.

Wenn Ihnen das Zen-Gedicht gefallen hat, gefällt Ihnen vielleicht auch Rootless Root: The Unix Koans of Meister Foo.


Häufig gestellte Fragen
F: Woran erkenne ich, ob ich bereits ein Hacker bin?
F: Bringen Sie mir bei, wie man hackt?
F: Wie kann ich dann anfangen?
F: Wann müssen Sie anfangen? Ist es zu spät für mich, um zu lernen?
F: Wie lange brauche ich, um Hacken zu lernen?
F: Ist Visual Basic eine gute Sprache für den Anfang?
F: Würden Sie mir helfen, ein System zu knacken, oder mir beibringen, wie man knackt?
F: Wie erhalte ich das Passwort für das Konto einer anderen Person?
F: Wie kann ich in die E-Mails einer anderen Person eindringen/diese lesen/überwachen?
F: Wie kann ich Channel-Op-Privilegien im IRC stehlen?
F: Ich bin geknackt. Helfen Sie mir, weitere Angriffe abzuwehren?
F: Ich habe Probleme mit meiner Windows-Software. Werden Sie mir helfen?
F: Wo finde ich echte Hacker, mit denen ich sprechen kann?
F: Können Sie nützliche Bücher über Hacking-bezogene Themen empfehlen?
F: Muss ich gut in Mathe sein, um Hacker zu werden?
F: Welche Sprache sollte ich zuerst lernen?
F: Welche Art von Hardware benötige ich?
F: Ich möchte einen Beitrag leisten. Können Sie mir helfen, ein Problem auszuwählen, an dem ich arbeiten kann?
F: Muss ich Microsoft hassen und verprügeln?
F: Aber wird Open-Source-Software Programmierer nicht dazu bringen, ihren Lebensunterhalt zu bestreiten?
F: Wo bekomme ich ein kostenloses Unix?
Q:

Woran erkenne ich, ob ich bereits ein Hacker bin?

Ein:

Stellen Sie sich die folgenden drei Fragen:

Sprechen Sie fließend Code?

Identifizieren Sie sich mit den Zielen und Werten der Hacker-Community?

Hat ein etabliertes Mitglied des Hackers Die Community hat dich jemals als Hacker bezeichnet?

Wenn Sie alle drei Fragen mit Ja beantworten können Fragen, Sie sind bereits ein Hacker. Zwei allein reichen nicht aus.

Beim ersten Test geht es um Fähigkeiten. Sie bestehen es wahrscheinlich, wenn Sie über die zuvor in diesem Dokument beschriebenen technischen Mindestkenntnisse verfügen. Sie blasen es direkt durch, wenn Sie eine beträchtliche Menge an Code hatten von einem Open-Source-Entwicklungsprojekt akzeptiert werden.

Der zweite Test betrifft die Einstellung. Wenn die fünf Prinzipien der Hacker-Denkweise für Sie offensichtlich, eher wie eine Beschreibung der Art und Weise, wie Sie bereits leben als alles Neue, du bist schon auf halbem Weg, es zu bestehen. Das ist die innere Hälfte; die andere, äußere Hälfte ist der Grad, in dem Sie Identifizieren Sie sich mit den langfristigen Projekten der Hacker-Community.

Hier ist eine unvollständige, aber indikative Liste einiger davon projects: Ist es Ihnen wichtig, dass sich Linux verbessert und verbreitet? Bist du Leidenschaft für Softwarefreiheit? Feindselig gegenüber Monopolen? Handeln Sie in der Überzeugung, dass Computer Instrumente der Ermächtigung sein können, die die Welt zu einem reicheren und menschlicheren Ort machen?

Aber hier ist ein Hinweis zur Vorsicht angebracht. Die Hacker-Community hat einige spezifische, in erster Linie defensive politische Interessen – zwei der sie verteidigen das Recht auf freie Meinungsäußerung und wehren sich gegen "geistiges Eigentum" an die Macht, die Open Source illegal. Einige dieser langfristigen Projekte sind Bürgerrechte Organisationen wie der Electronic Frontier Foundation und der die äußere Haltung schließt ihre Unterstützung ein. Aber darüber hinaus, Die meisten Hacker sehen Versuche, die Hacker-Haltung in eine explizites politisches Programm mit Misstrauen; Wir haben gelernt, die harten dass diese Versuche spaltend und ablenkend sind. Wenn jemand versucht, Sie zu rekrutieren, um im Namen der Hacker-Attitüde, haben sie das Wesentliche verfehlt. Die richtige Antwort ist wahrscheinlich "Halt die Klappe und zeig ihnen den Code."

Der dritte Test hat ein kniffliges Element der Rekursivität. Ich habe im Abschnitt "Was ist ein Hacker?" festgestellt, dass Hacker zu sein teilweise ein Zugehörigkeit zu einer bestimmten Subkultur oder einem sozialen Netzwerk mit eine gemeinsame Geschichte, ein Innen und ein Außen. In der fernen Vergangenheit haben Hacker waren eine viel weniger geschlossene und selbstbewusste Gruppe als heute. Aber die Bedeutung des Aspekts der sozialen Netzwerke hat im Laufe der Zeit zugenommen in den letzten dreißig Jahren, als das Internet Verbindungen mit der Kern der Hacker-Subkultur einfacher zu entwickeln und zu pflegen. Eine einfache Verhaltensindex des Wandels ist, dass wir in diesem Jahrhundert unsere eigene T-Shirts.

Soziologen, die Netzwerke wie die des Hackers untersuchen Kultur unter der allgemeinen Rubrik "unsichtbare Hochschulen" dass ein Merkmal solcher Netzwerke darin besteht, dass sie Gatekeeper haben — Kernmitglieder mit der sozialen Befugnis, neue Mitglieder zu unterstützen in das Netzwerk. Denn das "unsichtbare College", das Hacker ist Kultur ist eine lose und informelle, die Rolle des Gatekeepers ist auch informell. Aber eine Sache, die alle Hacker in ihrem Bones ist, dass nicht jeder Hacker ein Gatekeeper ist. Gatekeeper müssen ein gewisses Maß an Dienstalter und Leistung haben, bevor sie verleihen Sie den Titel. Wie viel ist schwer zu beziffern, aber jeder Hacker weiß wenn sie es sehen.

Q:

Bringen Sie mir bei, wie man hackt?

Ein:

Seit der ersten Veröffentlichung dieser Seite habe ich mehrere Anfragen erhalten. Woche (oft mehrere am Tag) von Leuten, die "mir alles über Hacking". Leider habe ich weder die Zeit noch die Energie dafür; meine eigenen Hacking-Projekte und die Arbeit als Open-Source-Befürworter, nehmen 110% meiner Zeit in Anspruch.

Selbst wenn ich es täte, ist Hacken eine Einstellung und Fähigkeit, die man im Grunde genommen muss Bringen Sie sich selbst bei. Sie werden feststellen, dass echte Hacker Ihnen helfen wollen, Sie werden dich nicht respektieren, wenn du darum bettelst, mit allem gefüttert zu werden, was sie tun wissen.

Lerne zuerst ein paar Dinge. Zeige, dass du es versuchst, dass du in der Lage, selbstständig zu lernen. Dann gehen Sie zu den Hackern, mit denen Sie sich treffen spezifische Fragen.

Wenn Sie einen Hacker per E-Mail um Rat bitten, gibt es zwei Dinge um es im Voraus zu wissen. Erstens haben wir festgestellt, dass Menschen, die faul oder nachlässig in ihrem Schreiben sind in der Regel zu faul und nachlässig in ihrem denken, um gute Hacker zu machen – also achten Sie darauf, richtig zu schreiben, und Verwenden Sie eine gute Grammatik und Zeichensetzung, sonst werden Sie wahrscheinlich ignoriert. Zweitens: Wagen Sie es nicht, nach einer Antwort zu fragen ein ISP-Konto, das sich von dem Konto unterscheidet, von dem aus Sie senden; Wir finden, dass Menschen, die das tun, in der Regel Diebe sind, die gestohlene Konten verwenden, und wir haben kein Interesse daran, Diebstähle zu belohnen oder zu unterstützen.

Q:

Wie kann ich dann anfangen?

Ein:

Der beste Weg für Sie, um anzufangen, wäre wahrscheinlich, zu einem LUG zu gehen (Linux-Benutzergruppe). Sie können solche Gruppen auf dem LDP General Linux finden Informationsseite; Es gibt wahrscheinlich einen in Ihrer Nähe, möglicherweise verbunden mit einem College oder einer Universität. LUG-Mitglieder werden wahrscheinlich geben Ihnen ein Linux, wenn Sie danach fragen, und wird Ihnen sicherlich helfen, eines zu installieren und legen Sie los.

Dein nächster Schritt (und dein erster Schritt, wenn du kein LUG in der Nähe findest) sollte sein, ein Open-Source-Projekt zu finden, das Sie interessiert. Beginnen Sie zu lesen Code und Überprüfung von Fehlern. Lernen Sie, einen Beitrag zu leisten, und arbeiten Sie sich ein.

Der einzige Weg dorthin besteht darin, daran zu arbeiten, Ihre Fähigkeiten. Wenn Sie mich persönlich um Rat fragen, wie Sie begonnen habe, werde ich Ihnen genau die gleichen Dinge sagen, weil ich nicht irgendwelche magischen Abkürzungen für Sie. Ich werde dich auch mental als wahrscheinlicher Verlierer - denn wenn Ihnen die Ausdauer fehlte, diese FAQ zu lesen und die Intelligenz, daraus zu verstehen, dass der einzige Weg Wenn Sie daran arbeiten, Ihre Fähigkeiten zu verbessern, sind Sie hoffnungslos.

Eine weitere interessante Möglichkeit ist der Besuch eines Hackerspace. Es gibt eine aufkeimende Bewegung von Menschen, die physische Orte - Maker's Clubs - an denen sie sich zum Arbeiten aufhalten können gemeinsam an Hard- und Softwareprojekten arbeiten oder alleine in einem Atmosphäre. Hackerspaces sammeln oft Tools und spezialisierte Ausrüstung, die für die Einzelpersonen zu besitzen. Hackerspaces sind im Internet leicht zu finden; Einer kann sich in Ihrer Nähe befinden.

Q:

Wann müssen Sie anfangen? Ist es zu spät für mich, um zu lernen?

Ein:

Jedes Alter, in dem Sie motiviert sind, anzufangen, ist ein gutes Alter. Die meisten Menschen zwischen 15 und 20 Jahren zu interessieren scheinen, aber ich kenne Ausnahmen in beide Richtungen.

Q:

Wie lange brauche ich, um Hacken zu lernen?

Ein:

Das hängt davon ab, wie talentiert Sie sind und wie hart Sie arbeiten es. Die meisten Menschen, die es versuchen, können in achtzehn Jahren respektable Fähigkeiten erwerben Monate bis zwei Jahre, wenn sie sich konzentrieren. Glauben Sie nicht, dass es hier endet, obwohl; Beim Hacken dauert es (wie in vielen anderen Bereichen) etwa zehn Jahre um Meisterschaft zu erlangen. Und wenn Sie ein echter Hacker sind, werden Sie den Rest ausgeben deines Lebens zu lernen und dein Handwerk zu perfektionieren.

Q:

Ist Visual Basic eine gute Sprache für den Anfang?

Ein:

Wenn Sie diese Frage stellen, bedeutet dies mit ziemlicher Sicherheit, dass Sie Ich denke darüber nach, unter Microsoft Windows zu hacken. Das ist ein schlechter Idee an sich. Als ich versuchte, zu lernen, wie man unter Windows hackt zu versuchen, tanzen zu lernen, während ich einen Gips trug, scherzend. Gehen Sie nicht dorthin. Es ist hässlich, und es hört nie auf, es zu sein hässlich.

Es gibt ein spezifisches Problem mit Visual Basic. hauptsächlich dass es nicht tragbar ist. Obwohl es einen Open-Source-Prototyp gibt Implementierungen von Visual Basic, den geltenden ECMA-Standards nicht mehr als einen kleinen Satz seiner Programmierschnittstellen abdecken. Auf Windows unterstützt den größten Teil seiner Bibliotheksunterstützung für einen einzelnen Anbieter (Microsoft); Wenn Sie nicht besonders vorsichtig sind, welche Funktionen Sie verwenden – vorsichtiger als alle anderen Neuling wirklich in der Lage ist – Sie werden am Ende in nur die Plattformen, die Microsoft unterstützt. Wenn Sie beginnend mit einem Unix, viel bessere Sprachen mit besseren Bibliotheken stehen zur Verfügung. Python zum Beispiel.

Außerdem ist Visual Basic wie andere Basics ein schlecht gestaltete Sprache, die Ihnen schlechtes Programmieren beibringt Angewohnheiten. Nein, verlangen Sie nicht, dass ich sie in Detail; Diese Erklärung würde ein Buch füllen. Lernen Sie eine gut gestaltete Sprache statt.

Eine dieser schlechten Gewohnheiten ist es, von einem einzigen abhängig zu werden Bibliotheken, Widgets und Entwicklungstools des Anbieters. Im Allgemeinen sind alle Sprache, die nicht mindestens unter Linux oder einem der BSDs vollständig unterstützt wird, und/oder der Betriebssysteme von mindestens drei verschiedenen Anbietern, ist ein schlechter eine, in der man lernen muss, sich einzuhacken.

Q:

Würdest du mir helfen, ein System zu knacken, oder mir beibringen, wie man knackt?

Ein:

Nein. Jeder, der nach der Lektüre dieser FAQ immer noch eine solche Frage stellen kann ist zu dumm, um erziehbar zu sein, selbst wenn ich die Zeit für Nachhilfe hätte. Alle E-Mail-Anfragen dieser Art, die ich erhalte, werden ignoriert oder antwortete mit äußerster Unhöflichkeit.

Q:

Wie kann ich das Passwort für das Konto einer anderen Person erhalten?

Ein:

Das ist ein Knacks. Geh weg, Idiot.

Q:

Wie kann ich in die E-Mails einer anderen Person eindringen/sie lesen/überwachen?

Ein:

Das ist ein Knacks. Verschwinde, du Idiot.

Q:

Wie kann ich Channel-Op-Privilegien im IRC stehlen?

Ein:

Das ist ein Knacks. Bitte, Kretin.

Q:

Ich bin geknackt. Helfen Sie mir, weitere Angriffe abzuwehren?

Ein:

Nein. Jedes Mal, wenn mir diese Frage bisher gestellt wurde, war es von einem armen SAP, der Microsoft Windows ausführt. Es ist nicht möglich, Windows-Systeme effektiv vor Crack-Angriffen schützen; den Code und Architektur haben einfach zu viele Mängel, was die Sicherung von Windows als würde man versuchen, ein Boot mit einem Sieb zu retten. Die einzige zuverlässige Prävention beginnt mit dem Wechsel zu Linux oder einem anderen System, das so konzipiert ist, dass es zumindest sicherheitsfähig ist.

Q:

Ich habe Probleme mit meiner Windows-Software. Werden Sie mir helfen?

Ein:

Ja. Gehen Sie zu einer DOS-Eingabeaufforderung und geben Sie "format c:" ein. Alle Probleme, die Sie haben Das Erleben hört innerhalb weniger Minuten auf.

Q:

Wo finde ich echte Hacker, mit denen ich reden kann?

Ein:

Am besten finden Sie eine Unix- oder Linux-Benutzergruppe in Ihrer Nähe und zu ihren Meetings gehen (Sie finden Links zu mehreren Listen von Benutzern, Gruppen auf der LDP-Website unter ibiblio).

(Ich habe hier immer gesagt, dass man im IRC keine echten Hacker finden würde, aber mir wurde zu verstehen gegeben, dass sich dies ändert. Anscheinend haben einige echte Hacker-Communities, die mit Dingen wie GIMP und Perl verbunden sind, haben IRC -Kanäle.)

Q:

Können Sie nützliche Bücher über Hacking-bezogene Themen empfehlen?

Ein:

Ich unterhalte ein Linux-Leselisten-HOWTO, das Sie hilfreich finden könnten. Die Loginataka könnte auch interessant sein.

Eine Einführung in Python finden Sie im Tutorial auf der Python-Website.

Q:

Muss ich gut in Mathe sein, um Hacker zu werden?

Ein:

Nein. Hacking verwendet sehr wenig formale Mathematik oder Arithmetik. Insbesondere benötigen Sie in der Regel keine Trigonometrie, Infinitesimalrechnung oder Analyse (es gibt Ausnahmen davon in einer Handvoll spezifischer Anwendungsbereiche wie 3D-Computergrafik). Kenntnis der formalen Logik und Boolesche Algebra ist gut. Einige Grundlagen in endlicher Mathematik (einschließlich endlicher Mengentheorie, Kombinatorik und Graphentheorie) hilfreich.

Viel wichtiger: Sie müssen logisch denken können und folgen Ketten exakter Argumentationen, wie es Mathematiker tun. Während der Inhalt der meisten Mathematik Ihnen nicht helfen wird, benötigen Sie die Disziplin und Intelligenz, um mit Mathematik umzugehen. Wenn es Ihnen an die Intelligenz, es gibt wenig Hoffnung für Sie als Hacker; Wenn Sie Fehlt die Disziplin, sollten Sie sie besser wachsen lassen.

Ich denke, ein guter Weg, um herauszufinden, ob Sie das Zeug dazu haben, ist die Auswahl ein Exemplar von Raymond Smullyans Buch What Is The Name Of Dieses Buch?. Smullyans spielerische logische Rätsel sind sehr ganz im Sinne von Hackern. In der Lage zu sein, sie zu lösen, ist ein gutes Zeichen; Spaß am Lösen ist noch besser.

Q:

Welche Sprache sollte ich zuerst lernen?

Ein:

HTML, wenn Sie es noch nicht kennen. Es gibt viele glänzende, hype-intensive schlechte HTML-Bücher da draußen, und erschreckend wenige gute. Diejenige, die ich mag am besten ist HTML: Die Definitive Anleitung.

HTML ist jedoch keine vollständige Programmiersprache. Wenn Sie bereit sind Um mit dem Programmieren zu beginnen, würde ich empfehlen, mit Python zu beginnen. Sie werden viel hören Leute, die Perl empfehlen, aber es ist schwieriger zu lernen und (meiner Meinung nach) weniger gut gestaltet.

C ist wirklich wichtig, aber es ist auch viel schwieriger als beides Python oder Perl. Versuchen Sie nicht, es zuerst zu lernen.

Windows-Benutzer, geben Sie sich nicht mit Visual zufrieden Grundlegend. Es wird Ihnen schlechte Gewohnheiten beibringen und es ist nicht übertragbar Fenster. Vermeiden.

Q:

Welche Art von Hardware benötige ich?

Ein:

Früher waren PCs eher leistungsschwach und Speicherarm, so dass sie die Lernprozess. Dies war Mitte der 1990er Jahre nicht mehr der Fall; jede Maschine ab einem Intel 486DX50 ist mehr als leistungsstark genug für die Entwicklung Arbeit, X und Internetkommunikation und die kleinsten Festplatten, die Sie Kaufen Sie heute sind groß genug.

Das Wichtigste bei der Auswahl einer Maschine, auf der Sie lernen möchten, ist ob seine Hardware Linux-kompatibel ist (oder BSD-kompatibel, sollte Sie entscheiden sich für diesen Weg). Auch dies gilt für fast alle modernen Maschinen. Die einzigen wirklich klebrigen Bereiche sind Modems und Wireless Karten; Einige Computer verfügen über Windows-spezifische Hardware, die nicht funktioniert mit Linux.

Es gibt eine FAQ zur Hardwarekompatibilität; Die neueste Version ist hier.

Q:

Ich möchte einen Beitrag leisten. Können Sie mir helfen, ein Problem auszuwählen, an dem ich arbeiten kann?

Ein:

Nein, weil ich Ihre Talente oder Interessen nicht kenne. Sie haben selbstmotiviert zu sein, sonst bleiben Sie nicht dabei, weshalb andere Menschen wählen Ihre Richtung fast nie.

Q:

Muss ich Microsoft hassen und verprügeln?

Ein:

Nein, das müssen Sie nicht. Nicht, dass Microsoft nicht abscheulich wäre, aber es gab eine Hackerkultur lange vor Microsoft und es wird noch lange danach eine geben Microsoft ist Geschichte. Jede Energie, die Sie darauf verwenden, Microsoft zu hassen, würde Seien Sie besser damit beschäftigt, Ihr Handwerk zu lieben. Schreiben Sie guten Code – das wird verprügeln Sie Microsoft ausreichend, ohne Ihr Karma zu beschmutzen.

Q:

Aber wird Open-Source-Software Programmierer nicht dazu bringen, ihren Lebensunterhalt zu bestreiten?

Ein:

Dies scheint unwahrscheinlich – bisher hat die Open-Source-Software Die Industrie scheint Arbeitsplätze zu schaffen, anstatt sie wegzunehmen. Wenn Ein Programm geschrieben zu haben, ist ein wirtschaftlicher Nettogewinn, wenn man es nicht hat geschrieben wird, wird ein Programmierer bezahlt, unabhängig davon, ob das Programm wird Open Source sein, nachdem es fertig ist. Und egal wie viel "freie" Software geschrieben wird, scheint es immer mehr Nachfrage nach neue und kundenspezifische Anwendungen. Ich habe mehr darüber auf den Open-Source-Seiten geschrieben.

Q:

Wo bekomme ich ein kostenloses Unix?

Ein:

Wenn Sie noch kein Unix auf Ihrem Computer installiert haben, An anderer Stelle auf dieser Seite füge ich Hinweise hinzu, wo man am meisten bekommt häufig verwendetes freies Unix. Um ein Hacker zu sein, braucht man Motivation und Eigeninitiative und die Fähigkeit, sich weiterzubilden. Jetzt loslegen...

<!---
MarcelRaschke/MarcelRaschke is a ✨ special ✨ repository because its `README.md` (this file)---!>
