# Entrega1_BrrasCruz

Esta es la primera entrega del proyecto final curso Python - Coderhouse

Instalación
Para poder visualizarlo debemos contar con

-Git

-VisualStudio Code, terminal o algún otro editor de código

-Django

Usage
Realizamos algunos imports que serán necesarios para la entrega final, pero que a efectos de esta entrega no utilizamos:

from django.views.generic import ListView

from django.views.generic.detail import DetailView

from django.views.generic.edit import CreateView

from django.urls import reverse_lazy

from django.views.generic.edit import UpdateView

from django.views.generic.edit import DeleteView

from django.http.request import QueryDict

from django.shortcuts import render, HttpResponse

from django.http import HttpResponse

from django.urls import path

from django.contrib import admin

from django.core.asgi import get_asgi_application

from django.db import models

from django import forms

from django.contrib import admin

from .models import *

Models
Contamos con 3 models:

class Libro class Autor class Genero

Página
La página emula una tienda de libros, contamos con distintas secciones:

#Libros path /libros

Donde se encontrará toda la información de los libros

Autores path /autores
Donde tendremos toda la información sobre los autores

Géneros path /genero
Donde tendremos toda la información sobre los géneros literarios

Forms
Contamos con 3 formularios para ingresar datos en los distintos models

Formulario de Libros path /libroFormulario Formulario de Autores path /autorFormulario Formulario de Género path /generoFormulario

Búsqueda
Por último, tenemos una búsqueda de libros path /busquedaLibro

Contribuciones
Cualquier contribución es bienvenida, por favor cargar un pull request.
