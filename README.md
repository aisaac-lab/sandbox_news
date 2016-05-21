# sandbox_news
gem install filewatcher
filewatcher *.haml "find . -name \*.haml -print | sed 'p;s/.haml$/.html/' | xargs -n2 haml"
