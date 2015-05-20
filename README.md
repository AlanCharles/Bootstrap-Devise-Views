# Bootstrap your Devise Views
If you're working with Devise then you will know that the forms it generates don't look the same as the other Bootstrap powered forms on your app. Here is a collection of Devise views which I've marked up with Bootstrap, copy them into your app and you'll have consistent looking forms in no time.

#### What do these replacement views actually change?
* replace devise's "field" class with Bootstrap's "form-group" class (for even spacing)
* remove `< br/>` after the field label (no need for these anymore)
* adds Bootstrap's `form-control` to each field (for even spacing)
* adds Bootstrap's `btn btn-default` class onto the buttons (for styling the buttons)
* adds placeholder text to each of the form fields (for usability)
* replaces italic 'helper' text with Bootstrap's text-info helper classe (for consistent styling)

## 1. Generate Devise Views
This generator copies all of Devise's views into your views folder. This means you can edit them how you like (or in this case, replace them with Bootstrap versions)

```ruby
rails g devise:views
```

## 2. Replace all the Devise views with these Bootstrapped ones
1. Replace `devise/confirmations/new.html.erb`
1. Replace `devise/passwords/edit.html.erb`
1. Replace `devise/passwords/new.html.erb`
1. Replace `devise/registrations/edit.html.erb`
1. Replace `devise/registrations/new.html.erb`
1. Replace `devise/sessions/new.html.erb`
1. Replace `devise/shared/_links.html.erb`
1. Replace `devise/unlocks/new.html.erb`

