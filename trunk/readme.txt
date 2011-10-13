useful usage:
link ltr_finder and genome_plot.pl
./ltr_finder TestSet/yeast.fa -PCHR10 -w2 -f /dev/stderr 2>&1 >fig_test/result.txt | perl genome_plot.pl fig_test/

algorithm
get pair
join pair(also cut at possible gap)
extend pair
find edge
find TG..CA and TSR
find signal(find PBS and PPT)
find RT
find IN(core) IN(c-term) RH(if -a)
output with restrict

can read multi sequence now
predict domains
modify SuffixArray function, no longer change input string
stdaln can handle NNNN vs atcg
delete exact match pairs that contain Ns

fix bug:
handle 'NNNNNNN' before local_align

