# Etelä-Espoon sosialidemokraattinen työväenyhdistys r.y., esityslistat ja pöytäkirjat

## Tarvittavat ohjelmistot

Nämä tiedostot ovat LaTeX-tekstinkäsittelyohjelman lähdekoodimuodossa. Niitä varten pitää olla asennettuna LaTeX-järjestelmä.

### Microsoft Windows-koneet

Jompikumpi seuraavista:

* [TeXLive for Windows](https://www.tug.org/texlive/windows.html#w64)
* [MikTeX](https://miktex.org/download)

### Ubuntu Linux-koneet

```bash
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt-get install texlive-full
```

### RedHat Linux-koneet

```bash
sudo yum install -y texlive
```

## Kääntäminen pdf-muotoon

```bash
pdflatex <tiedosto>.tex
```
tarvittaessa useampaan kertaan hakemiston muodostamiseksi oikein.
