# web-082817-intro-to-oo

Define a method `Book.all` that works like this:

Book.new('gravitys rainbow', ['thomas pynchon'])
Book.new('mason & dixon', ['thomas pynchon'])
Book.new('calvin and hobbes anthology', ['bill watterson'])

after i do this above,
I would expect that calling `Book.all`
would return an array with the 3 newly created books inside
[<Book @title='gravitys rainbow'>, <Book @title='mason & dixon'>, <Book @title='calvin and hobbes'>]

Book.all.first.class == Book
=> true
