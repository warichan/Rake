# encoding: utf-8
desc "main.cをコンパイルする"↲
CC = "gcc"↲
task :main => "main.o"↲
file "main.o" => "main.c" do↲
  sh "CC -c -o main.o main.c"↲
end↲
