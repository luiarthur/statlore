.PHONY: clean serve clean-serve

all: clean-serve

PORT = 4012
LIVE_RELOAD_PORT = 4022

clean:
	rm -rf _site

serve:
	bundle exec jekyll serve --port $(PORT) --incremental \
		--livereload --livereload-port $(LIVE_RELOAD_PORT)

clean-serve: clean serve

update-gems:
	rm Gemfile.lock
	bundle install

install:
	bundle install
