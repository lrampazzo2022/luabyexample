---
title: "Lua for Configuration"
weight: 29
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Lua for Configuration

Using Lua as a configuration language is often the first step toward
a fully scriptable application.
Lua is licensed under the [MIT license](https://www.lua.org/license.html)
which explicitly permits commercial use. Some examples:

## Neovim

Neovim [uses Lua extensively](https://neovim.io/doc/lua-resources/).
It can for instance load its configuration from an init.lua instead of the
traditional init.vim.
There are [a lot of plugins](https://github.com/search?l=Lua&q=neovim&type=Repositories)
for Neovim written in Lua.

## MPV and VLC

Both [MPV](https://github.com/mpv-player/mpv/blob/master/DOCS/man/lua.rst)
and [VLC](https://wiki.videolan.org/Documentation:Building_Lua_Playlist_Scripts/)
use Lua as a main scripting language.

## Nginx

[ngx_http_lua_module](https://github.com/openresty/lua-nginx-module) allows
to embed lua into NGINX HTTP servers.
It is part of [OpenResty](https://github.com/openresty/openresty) - high
performance web platform based on Nginx and LuaJIT.

## Redis

Redis allows
[adding functionality with Lua](https://redis.com/ebook/part-3-next-steps/chapter-11-scripting-redis-with-lua/)

## And more

There is even [browser](https://github.com/luakit/luakit) and [code editor](https://github.com/rxi/lite) written in Lua.
