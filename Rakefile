# encoding: utf-8
desc "main.cをコンパイルする"↲
CC = "gcc"↲

task :default => "main"
↲
file "main" => "main.o" do↲
  sh "#{CC} -o main main.o"
end

file "main.o" => "main.c" do
  sh "#{CC} -c main.c"↲
end↲
