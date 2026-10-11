#Dev
###\*manually open "localhost://9000"
##Linuix/Mac: clj -M -m cljs.main --serve
##Windows: java -cp "cljs.jar;src" cljs.main --serve

#Dev with REPL command prompt
###\*REPL: clojure comman prompt (ClojureScript version of normal browser console)
##Linuix/Mac: clj -M --main cljs.main --compile hello-world.core --repl
##Windows: java -cp "cljs.jar;src" cljs.main --compile hello-world.core --repl

#Build
##Linuix/Mac: clj -M -m cljs.main --optimizations advanced -c hello-world.core
##Windows: java -cp "cljs.jar;src" cljs.main --optimizations advanced -c hello-world.core

#'Hot' reload: (require '[hello-world.core :as hello] :reload)
