# .github
Badania kliniczne, polityka prywatności, produkt medyczny, regulaminy stron, testy wydajnościowe, akredytacje samochodów 

raporty z testów bezpieczeństwa samochodów: https://www.euroncap.com/en/

baza danych z certyfikatami produktów medycznych w UE: https://ec.europa.eu/tools/eudamed/#/screen/home (Nie wiem czy to się przyda czy nie, ale są tu jakieś dokumenty)



unit testy, generator test casow (dokumentow), z parametrami - opcje dodawania obrazow szumu do danych itd, 



dodac barplota, walidacja xmla, maly druczek dodatkowo do dokumentow, tabela, rozdzielic rysunek od wizualizacji, listy numerowane/punktowane



edycja w locie xml (edytor), sprobowac utworzyc dokumenty podobne do dokumentow faktycznych, xps zobaczyc.



---

4. STEPS
    1) Generate template of a document along with validations based on a few provided examples by the user (allow for internet search and so on to suggest validations that are more complex - todo if the time allows)
    2) Edytor - allow manual edition of the template along with the chat between user and llm to change some major  parts of the template
    3) Generate documents based on users data and the approved template
    4) Validate generated documents based on the validations created in the first step

Kajetan first finish what we have in terms of basic document generation (generation of documents without the llm based solely on data), then start working on document generation with the llm along with some very basic validations - specific variables are ints float s strings graphs etc. 

Mikolaj start working on the editor and the overall web app for the whole system then connect with Kajetan in terms of testing the llm models and capabilities, so that a single llm can be used for both generation and edition of the template
