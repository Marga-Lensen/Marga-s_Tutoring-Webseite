# Markdown Tipps & Tricks I - screenshots einfuegen

## Vorgehensweisen:
##### (Anwendungsbeispiel: Webseite checken mittels https://pagespeed.web.dev/)
### 📚️ Screenshot machen, speichern und einfügen:
- auf der Webseite (https://pagespeed.web.dev/) macht man ein ***screenshot***; findet es in ***Downloads***, kopiert/verschiebt es ins Projekt, z.B. in den Ordner `readme`. 
- in der Markdown Datei fügt man das Bild mit dem Pfad `<src/readme/Screenshot 2024-07-05 at 14-47-40 PageSpeed Insights.png>` ein.

###  💡 simple, simple Alternative 😉

 - anstatt das screenshot zu machen, aus den Downloads zu kopieren und hier in das Projekt hinzuzufügen, kann man das 
 ```css
 screenshot DIREKT MIT 'Strg + V' EINFÜGEN! 😎
 ```

![alt text](image-1.png)

 - Der Inhalt (das screenshot: `![alt text](image-2.png)`) wird Außerdem automatisch gespeichert!😀
 - die screenshots image-n.png kann man einfach verschieben (`drag & drop `zum Ordner `readme`), und von dort einfach erneut in die Markdown Datei einfügen (wieder mit `drag & drop`; `Shift` drucken um es zu platzieren); es passt seinen Pfad automatisch an ( `![alt text](src/readme/image-2.png)` )!🤓

#
#### Anwendungsbeispiel: Webseite checken mittels (https://pagespeed.web.dev/):

-  Landing Page (home; `index.html`); Leistung auf *desktop*: 
![alt text](src/readme/image-2.png)

- Landing Page (home; `index.html`); Leistung auf *mobile device*: 
![alt text](src/readme/image-3.png)

-  eine Unterseite bzw. eine andere Seite (hier: `/links.html`); Leistung auf *desktop*: 
![alt text](<src/readme/Screenshot 2024-07-05 at 14-47-40 PageSpeed Insights.png>)

- eine Unterseite bzw. eine andere Seite (hier: `/Pause.html`); Leistung auf *mobile device*: 
![alt text](src/readme/image-4.png)
#
