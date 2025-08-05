# DRF---Facing-Problems
My porpuse with this repo is to documented some of some problems/error codes that I would be facing right now while I'm developing Django Rest Framework, this one at the moment will be here in the readme of this file but than I would be creating an interactive web page to put my current problems, what appears those problems and how do I resolve it.


# TemplateDoesNotExist

I think that this one is one of the current ones, we're working on the start of the project without precupation at all untill this error, happen. 
[NSERT IMAGE]

It basically didn't stop the development server the we start but still our DRF interface didn't show, so what happened?

- We know that we're using DRF of course, but does Django knows? if you has worked with Django before you will know already what is happing here, if this the first time that you're using DRF I'll explain you ->
- Basically django needs to have like an inventory of each new library that is currently installed or in other case using, so we need to tell python that we're using DRF by placing 'rest_framework' in the settings folder in the INSTALLED_APPS list. After that you'll be able to see now the DRF interface.
