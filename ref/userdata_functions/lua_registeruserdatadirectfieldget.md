---
name: lua_registeruserdatadirectfieldget
ret: int
stack: "-0, +0, -"
args:
  - name: L
    type: lua_State*
    desc: Lua thread
  - name: tag
    type: int
    desc: Userdata tag
  - name: field
    type: const char*
    desc: Field
  - name: fn
    type: lua_UserdataDirectFieldGet
    desc: Getter function
---

TODO.
