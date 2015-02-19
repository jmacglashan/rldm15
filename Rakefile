desc "build the pdf"
task :default => [] do
  sh "pdflatex groundhog.tex"
  sh "pdflatex groundhog.tex"
  sh "bibtex groundhog"
  sh "bibtex groundhog"
  sh "pdflatex groundhog.tex"
  sh "pdflatex groundhog.tex"
end


task :clean do
  sh "rm -rf *.aux *.bbl *.blg *.log"
end
