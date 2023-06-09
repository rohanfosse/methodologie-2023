FROM jekyll/jekyll:latest

WORKDIR /srv/jekyll

COPY . .

# Installer les gems nécessaires
RUN bundle install

RUN jekyll build

EXPOSE 4000

CMD ["jekyll", "serve", "--host", "0.0.0.0"]