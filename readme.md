# Respuestas Practica Git

## Comando en paso 11

```
get reset --hard HEAD~1
```
De esta manera perdemos los cambios realizados en el working copy\
como se nos pidio

## Comando(s) paso 12

```
git reflog + git reset < id commit>
```
Con git reflog buscamos el commit al que queremos it, el que ha sido\
eliminado y con reset nos movemos con la rama styled a ese commit

## Merge paso 13

No causo ningun conflicto. Los cambios solo se realizaron en styled\
por lo que master simplemente se puso al dia

## Merge paso 19

CONFLICTO. Al haber hecho otra rama con cambios con commit, hizo\
conflicto con los cambios de styled.

## Merge paso 21

No, master sigue poniendose al dia con el resto ya que todavia no se\
ha hecho cambios en master

## Comando paso 25

```
git log --graph
```
## Merge paso 26

```
git merge --no-ff title
```
Si, se podria haber hecho fast forward ya que se mantenian en la misma\
linea y al, master, no sufrir cambios, se habria actualizado

## Comando(s) 27

```
git reset <id commit>
```

## Comando(s) 28

```
git reset --hard HEAD~1
```

## Comando(s) 29

```
git branch -D title
```
## Comando(s) 30

```
git reflog + git reset <id commit>
```

## Comando(s) 32

```
git reflog + git checkout <id commit>
```

## Comando(s) 33

```
git reflog + git checkout <id commit>
```
