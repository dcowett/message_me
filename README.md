# README


1. run  rails generate model Message

  Running via Spring preloader in process 36669
        invoke  active_record
        create    db/migrate/20201210123028_create_messages.rb
        create    app/models/message.rb
        invoke    test_unit
        create      test/models/message_test.rb
        create      test/fixtures/messages.yml

2. Add entries to model file (relationships, validations, etc...)

3. Add attribute entries to migration file

4. run  rails db:migrate

  The dependency tzinfo-data (>= 0) will be unused by any of the platforms Bundler is installing for. Bundler is installing for ruby but the dependency is only for x86-mingw32, x86-mswin32, x64-mingw32, java. To add those platforms to the bundle, run `bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java`.
  == 20201210123028 CreateMessages: migrating ===================================
  -- create_table(:messages)
     -> 0.0017s
  == 20201210123028 CreateMessages: migrated (0.0019s) ==========================
