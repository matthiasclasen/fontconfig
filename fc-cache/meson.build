fccache = executable('fc-cache', ['fc-cache.c', fcstdint_h, alias_headers, ft_alias_headers],
  include_directories: [incbase, incsrc],
  link_with: [libfontconfig],
  c_args: c_args,
  install: true,
)

tools_man_pages += ['fc-cache']
