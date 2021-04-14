# Description

This md describe how to create django template.

## Create a template

1. To create a template, create a folder called "templates" under an application.

2. then, you create a new folder under templates and called app name. (for example, website)

3. create a HTML 5 file which is same name as application.

use get_object_or_404 to handle error


## View

View has 3 things.

1. Behaviour
2. Pythhon function
3. Mapped to URL

## Template

1. Presentation
2. Generates HTML

## Model

1. Data
2. Model classes

## Retrieving Model DAta

1. Get all objects
   meetings = Meeting.objects.all()

2. Get object count
   num_meetings = Meting.objects.count()

3. Get a specific object
   Meeting = Meeting.objects.get(pk=5) (pk means primary key)
   