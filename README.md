# Домашни

Това хранилище съдържа домашните работи от курса [Програмиране с Ruby](http://fmi.ruby.bg). Тук може да намерите условия, тестове и решения.

Всяко домашно се намира в директория с поредния си номер.

## Изпълняване на примерните тестове

За да изпълните примерните тестове, трябва да си качите [rspec](https://www.relishapp.com/rspec). За целта, просто изпълнете:

    $ gem install rspec

Ако вашия код се съдържа в `solution.rb`, намиращ се в текущата директория, може да изпълните примерния тест така:

    $ rspec sample_spec.rb --require ./solution.rb --colour --format documentation

Обърнете внимание, че `solution.rb` трябва да е в текущата директория и трябва да се реферира като `./solution.rb`.

Още инструкции може да прочетете в [ръководството за предаване на домашни](http://fmi.ruby.bg/tasks/guide).
