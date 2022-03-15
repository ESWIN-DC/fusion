t = []
foreach i : ['execlog', 'hotblocks', 'hotpages', 'howvec', 'lockstep', 'hwprofile', 'cache']
  t += shared_module(i, files(i + '.c'),
                     include_directories: '../../include/qemu',
                     dependencies: glib)
endforeach
