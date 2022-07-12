<header> defines a header for the document or a section
<footer> defines a footer for the document or a section
<nav> defines navigation links in the document
<main> defines the main content of a document
<section> defines a section in the document—the spec defines this as “a thematic grouping of content, typically with a heading," so you can think of it as being like a chapter
<article> defines an article in the document
<aside> defines content aside from the page content
<address> defines the contact information for the author/owner of a document or an article
<figure> defines self-contained content, like illustrations, diagrams, photos, code blocks, etc.

> git clone git@github.com:AdamStrzyzewski/live-repo.git
> touch index.html // utworzenie pliku
> git status

> git add .

> git commit -m // message
> git commit -m "feat: initialization-added index html"
feat: initialization added index html // feature
fix: // naprawa błędu w kodzie
chore: // nieprzyjemny obowiązek
documentation
> git commit -me // pustą wiadomość
> git push

> git checkout master // istniejący branch 
> git checkout -b feat/change-text-color
feat/change-text-color // feature
fix/stop-server-from-blowing-up 
// naprawa błędu w kodzie
chore/change-css-paths
// nieprzyjemny obowiązek
documentation

3 główne branche
master
staging
dev

Pull Request (github) === Merge Request (gitlab)

https://github.com/AdamStrzyzewski/new-test-repo/tree/master
https://github.com/AdamStrzyzewski/live-repo

WSL


<body>
<section>
 <div class="container">
  treść sekcji
 </div>
</section>
</body>