# cine.io Example Application in Sinatra

This repository demonstrates the use of the [cine.io Ruby SDK][cineio-ruby] for a simple app that can create streams, publish to them, and play them back.

## How to Use

1. Sign up for your own API key at [cine.io][cineio].
2. Set up your environment:

      ```term
      $ export CINE_IO_PUBLIC_KEY='<your cine.io project public key>'
      $ export CINE_IO_SECRET_KEY='<your cine.io project secret key>'
      ```

3. Bundle your gems:

      ```term
      $ bundle install
      ```

4. Run the server:

      ```term
      $ ruby server.rb
      ```

<!-- external links -->
[cineio]:https://www.cine.io/
[cineio-ruby]:https://github.com/cine-io/cineio-ruby
