### core


1. slackware64-current/source/ap/slackpkg patches:
   -  adding the file `/etc/slackpkg/whitelist`. Package names listed in whitelist escaping from blacklist even if entaire set is blacklisted. (kde/ x/ etc..)
 
2. slackware64-current/source/sysvinit-scripts/scripts patches:
   -  for better stability (althought current script is stable as always.)
   
3. slackware64-current/source/a/aaa_base patches:
   -  adding slackware_logo.png path in os-release.
   
4. a/etc/_etc.tar.gz
   - Ensure XDG_RUNTIME_DIR is set in `/etc/profile`

---

### 3rd

1. sbopkg /usr/sbin/sqg
   - made `sqg -a` to use half of avaliable cpu threads, else use only 1 ...
