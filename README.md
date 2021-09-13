# PHP FFI aneb proč (ne)volat C kód z vašich webovek
PHP 7.4 přineslo mnoho nových zajímavých vlastností a jednou z nich je zahrnutí Foreign Function Interface (FFI) přímo do jádra PHP. Jaké problémy má ale tato nová funkcionalita řešit? Znamená to, že již nebudeme muset psát rozšíření PHP, pokud bychom chtěli používat existující knihovnu?

V tomto wokshopu společně na praktickém příkladě zjistíme, jak snadno volat téměř libovolnou knihovnu jazyka C přímo z jazyka PHP. Jak překonat běžná úskalí a co dělat když věci nedaří.
Třešničkou na dortu bude seznámení se s DuckDB embeded OLAP databází, vycházející hvězdou datové analýzy.

## Obsah repozitáře
Tento repozitář obsahuje veškeré nutné soubory a nástroje pro to abyste se mohli účastnit workshopu "PHP FFI aneb proč (ne)volat C kód z vašich webovek" 

## Spuštění Docker containeru s předpřipraveným prostředím
Ke spuštění budete potřebovat Docker a Docker compose. Pokud docker nemáte většinu workshopu lze absolvovat v Linuxu s PHP ve verzi 8.0. Windows bez Dockeru nejsou bohužel podporovány, lze však použít WSL anebo Vagrant. 

```bash
docker-compose run cli
```
