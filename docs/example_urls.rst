.. code::

  urlpatterns = patterns('',
      url(r'^$', views.choose, name='choose'),
      # Add the url-pattern as generated by the filechooser
      views.filechooser().url_pattern()
  )
