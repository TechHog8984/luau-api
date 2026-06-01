---
name: lua_registeruserdatadirectaccess
ret: int
stack: "-0, +0, -"
args:
  - name: L
    type: lua_State*
    desc: Lua thread
  - name: tag
    type: int
    desc: Userdata tag
  - name: get
    type: lua_UserdataDirectAccess
    desc: Getter
  - name: set
    type: lua_UserdataDirectAccess
    desc: Setter
  - name: namecall
    type: lua_UserdataDirectNamecall
    desc: Namecall
---

TODO.
