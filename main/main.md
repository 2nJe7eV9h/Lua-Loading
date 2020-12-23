local label = script.Parent.NameOfLabel 
local frame = script.Parent 
local frameToLoad = script.Parent.Parent.ThingToBeOpened

label.Text == "Loading."
wait(1)
label.Text == "Loading.."
wait(1)
label.Text == "Loading..."
wait(1)
label.Text == "Loading."
wait(1)
label.Text == "Loading.."
wait(1)
label.Text == "Loading..." 
wait(1)
label.Text == "_____ is Loaded!"
wait(1.2)
frameToLoad.Visible = true
frame.Visible = false
