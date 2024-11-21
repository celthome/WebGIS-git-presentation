# WebGIS-git-presentation

## Aufgabenstellung
Klont das Repository.  
Erstellt eine neue Branch mit eurem Namen als Namen.  
Fügt in den Ordner *images* ein Bild eures (Wunsch-)Haustieres ein.  
Speichert es in euer lokales Repository. Anschließend merges es in `main`.


## Cheat Sheet
<details>
  <summary> :memo: Hilfestellung </summary>

```python
cd /path/to/destination/where/you/want/to/clone
```

```python
git clone URL
```

```python
git branch your-name
```

```python
git checkout your-branch
```

> Fügt euer Bild hinzu

```python
git status
```

```python
git add your-image
```

```python
git commit -m "message with comment on change"
```
> Jetzt ist das Bild in eurem lokalen Repo gespeichert.

```python
git checkout main
```
> :warning: Wichtig, weil wir alle gleichzeitig arbeiten und evtl. schon Änderungen vorgenommen wurden. 
> ```python
> git pull origin main
> ```

```python
git merge your-branch
```

```python
git push origin main
```
> Jetzt ist euer Bild in dem zentralen Repository.

</details>
