A library for making epubs that actually works in 3.4.1.

For now, I'm being lazy and just copying the mimetype and container.xml instead of writing it every time.

It's relatively simple.
```python
exampleEpub = Epub()
exampleEpub.addAuthor("Me")
exampleEpub.addTitle("A Book")
exampleEpub.addPublisher("The Publisher")
exampleEpub.addHTML('filepath_of_xhtml_file', 'optional_title')
exampleEpub.addIMG('filepath_of_img')
exampleEpub.create()
```