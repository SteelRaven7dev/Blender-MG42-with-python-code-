# Blender-MG42-with-python-code-
Low poly simple mg42 with firing mechanism ( edit: partially since upadate to blender) in , works in all IDEs' and can be used in conjuncition with a javascript parse command which  is below:
(LUA CODE)
#h being the input variable.
begin function(h)
import new part="h"
if h= nil/false
script/touched.Parent.Humanoid:Connect(h)
wait 1s
parse(H)
end)
