Add this to .zshrc:

	export RUBYLIB=$HOME/github/gollum/extensions/wikicloth-master/lib
	export RUBYLIB=$RUBYLIB:$HOME/github/gollum/extensions/twitter-text-master/rb/lib
	export RUBYLIB=$RUBYLIB:$HOME/github/gollum/extensions/ruby-unf-master/lib
	export RUBYLIB=$RUBYLIB:$HOME/github/gollum/extensions/htmlentities-master/lib
	export RUBYLIB=$RUBYLIB:$HOME/github/gollum/extensions/expression_parser-master/lib
	
Then open:

	http://localhost:4567/