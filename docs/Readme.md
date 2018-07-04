## Build Documentation:

#### Install Requirements

```python
pip install -r docs/requirements.txt
```
#### Build Documentation
Create a dir,and copy all the things in the Template to the dir
```python
# Enter root folder.
python generate.py language option
```
Example:   
to build Chinese document project at the first time,use
```python
python generate.py zh fbuild
```
when you modify po files and you want to regenerate the mo files ,use
```python
python generate.py zh update
```
when the main project(Matchzoo) update,use
```python
python generate.py zh rebuild
```



