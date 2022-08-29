# Lern-Bericht
Soldo Maria

## Einleitung

Im Modul 133 geht es um Web-Applikation mit Session-Handling zu realisieren. In diesem Lerbericht werde ich Ihnen zeigen was ich alles im Laufe diese Modules gelernt habe.

## Was habe ich gelernt?

In diesem Modul habe ich ich zum Bespiel, outputLabels, InputTexte und commandLinks gelernt.

## Beschreibung

Auf einer Seite sieht man Text (auch mit einer SessionId), einen Feld wo man einen Inout geben kann (hier den Nachnamen) und einen Link. Dieser soll dann zur andere Seite führen.

##### Das ist der Code:
``` Java
        <h:form> 
            <!-- output SessionId-->
            <h:outputLabel id="id" value="Ihre Sitzung wurde eröffnet: #{helloManagedBean.id}"/> 
            <br/>
            <h:outputLabel for="nachname" value="Ihr Nachname"/> 
            <!-- Input for lastname with a Bean-->
            <h:inputText value="#{helloManagedBean.nachname}" id="nachname"/>
            <br/>
            <!-- Link to next Site-->
            <h:commandLink value="Schritt 2" action="schritt2.xhtml"/>
        </h:form>
```

##### So sieht es aus:
<img width="362" alt="image" src="https://user-images.githubusercontent.com/69591610/187167402-dde97ad9-4dad-4f4e-b6a0-7a1f1504e926.png">

* blau: Hier sieht man wie der <h: outputLabel> den Text und die SessionId herausgibt.
* pink: Hier sieht man, dass man einen Nachnamen eingeben kann (<h: inputText>).
* grün: Das ist der <h: commandLink>. Dieser Link führt zu der nächsten Seite.

## Verifikation

Mit diesen Medien kann ich zeigen, dass ich mit outputLabels, InputTexte und commandLinks arbeiten kann.

# Reflektion zum Arbeitsprozess

* 👍 Immer pünktlich in den Unterricht gekommen.
* 👍 Schnell und Richtig die JDK und das NetBeans installiert und mit Glasfish eingerichtet.

* 👎 Brauche einwenig lange um es zu verstehen / mit dem zuarbeiten.

##### Verbesserungsvorschlag:
Weiter im meinem Tempo arbeiten, aber doch sich auch mehr Mühe zugeben.

