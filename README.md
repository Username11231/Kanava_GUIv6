local VLib = loadstring(game:HttpGet("https://pastebin.com/raw/Mb49kKTP"))()


		MAINTTL = "КАНАВА" 

local win = VLib:Window("By XJle6220923", Color3.fromRGB(196, 40, 28))

local exit = win:Tab("Закрытие")
local main = win:Tab("Основное")
local fun = win:Tab("Веселье")
local tp = win:Tab("Телепортации")
local m = win:Tab("Звуки")
local s = win:Tab("Секреты (Не работает")

exit:Button("Закрыть менюшку",function()
game.CoreGui["Library"]:Destroy()
end)

 
main:Button("Анти-канава-килл", function(table)
    game.Workspace.startPart:Destroy()
    game.Workspace.Kil:Destroy()
end)

main:Button("Анти-река",function(table)
    game.Workspace.RagdollParts:Destroy()
    game.Workspace.KillParts:Destroy()
end)

main:Button("Анти-костёр",function(table)
    game.Workspace.FireParts:Destroy()
end)

main:Button("Подобрать все оружия",function(table)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
game.Workspace.Folder:Destroy()
wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Workspace.Folder.Handle.CFrame
end)

main:Toggle("Скорость",function(t)
    if t then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 75
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end
end)

main:Toggle("Ноуклип",function(t)
    if t then
        local player = game.Players.LocalPlayer.Character
player.Torso.CanCollide = false
player.Head.CanCollide = false
    else
        local player = game.Players.LocalPlayer.Character
player.Torso.CanCollide = true
player.Head.CanCollide = true
    end
end)

fun:Button("Удалить деревья",function(table)
    game.Workspace.Trees:Destroy()
end)

fun:Button("Включить свою эмоцию",function(table)
    game:GetService("ReplicatedStorage").Remotes.Emote:FireServer()
end)

fun:Button("Откидывание/FlingGUI",function(table)
    loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()
end)

fun:Toggle("Фейковое зависание/FakeLag",function(t)
    if t then
        local player = game.Players.LocalPlayer.Character
player.HumanoidRootPart.Anchored = true
    else
        local player = game.Players.LocalPlayer.Character
player.HumanoidRootPart.Anchored = false
    end
end)

fun:Button("Бухнуть",function(table)
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Username11231/Username11231/main/README.md'))()
end)

tp:Button("Крыша гаража",function(table)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(87.383728, 2071.49951, 24.7613411, -0.0666142404, -4.14379286e-08, 0.997778833, 1.14683509e-07, 1, 4.91867347e-08, -0.997778833, 1.17705312e-07, -0.0666142404)
end)

tp:Button("Крыша квартиры",function(table)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-230.917465, 2100.49878, 198.908508, 0.0226848181, 1.04653441e-08, -0.999742687, 1.28491422e-08, 1, 1.07595941e-08, 0.999742687, -1.30899149e-08, 0.0226848181)
end)

tp:Button("Спрятаться",function(table)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-21.6261234, -10236.9316, -71.4428253, 0.169004753, 0.141610011, -0.975389123, -3.63696656e-10, 0.989624679, 0.143676758, 0.985615253, -0.024282055, 0.167251274)
end)

tp:Button("В подвал",function(table)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-214.039612, 2061.49976, 224.547104, -0.998698115, 0, -0.0510110706, 0, 1, 0, 0.0510110706, 0, -0.998698115)
end)

fun:Button("Ресет",function(table)
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
end)

m:Button("БАЛЯЯЯЯТЬ",function(table)
    game:GetService("ReplicatedStorage").Sounds["5"].Playing = true
end)

m:Button("ОТКРЫТИЕ МАГАЗА",function(table)
    game:GetService("ReplicatedStorage").Sounds.BSDMWO.Playing = true
end)
m:Button("УДАР БИТОЙ",function(table)
    game:GetService("ReplicatedStorage").Sounds.BatHit.Playing = true
end)
m:Button("СМЕРТЬ",function(table)
    game:GetService("ReplicatedStorage").Sounds.Bell.Playing = true
end)
m:Button("УДАР МОЛОТКОМ",function(table)
    game:GetService("ReplicatedStorage").Sounds.Bonk.Playing = true
end)
m:Button("Bruh",function(table)
    game:GetService("ReplicatedStorage").Sounds.Bruh.Playing = true
end)
m:Button("Щёлк",function(table)
    game:GetService("ReplicatedStorage").Sounds.Camera.Playing = true
end)
m:Button("СТРАШНО ВЫРУБАЙ",function(table)
    game:GetService("ReplicatedStorage").Sounds["Creepy Hit 4"].Playing = true
end)

m:Button("Закрытие двери",function(table)
    game:GetService("ReplicatedStorage").Sounds.DoorClose.Playing = true
end)

m:Button("Тук-тук-тук",function(table)
    game:GetService("ReplicatedStorage").Sounds.DoorKnock.Playing = true
end)

m:Button("Открытие дверцы",function(table)
    game:GetService("ReplicatedStorage").Sounds.DoorOpen.Playing = true
end)

m:Button("Поедание",function(table)
    game:GetService("ReplicatedStorage").Sounds.Eat.Playing = true
end)

m:Button("Мишка Фреди",function(table)
    game:GetService("ReplicatedStorage").Sounds["Five nights at Freddy's: Power out"].Playing = true
end)

m:Toggle("Пожар (Бесконечно)",function(t)
    if t then
        game:GetService("ReplicatedStorage").Sounds.FireLoop.Playing = true
    else
        game:GetService("ReplicatedStorage").Sounds.FireLoop.Playing = false
    end
end)


m:Button("Бравл1",function(table)
    game:GetService("ReplicatedStorage").Sounds.Harmonica.Harm1.Playing = true
end)


m:Button("Бравл2",function(table)
    game:GetService("ReplicatedStorage").Sounds.Harmonica.Harm2.Playing = true
end)


m:Button("Бравл3",function(table)
    game:GetService("ReplicatedStorage").Sounds.Harmonica.Harm3.Playing = true
end)


m:Button("Бравл4",function(table)
    game:GetService("ReplicatedStorage").Sounds.Harmonica.Harm4.Playing = true
end)


m:Button("Удар битой",function(table)
    game:GetService("ReplicatedStorage").Sounds["Metal hit"].Playing = true
end)


m:Button("Удар сковородой",function(table)
    game:GetService("ReplicatedStorage").Sounds.Pan.Playing = true
end)


m:Button("Звук свиньи",function(table)
    game:GetService("ReplicatedStorage").Sounds.Pig.Playing = true
end)


m:Button("Звук банана",function(table)
    game:GetService("ReplicatedStorage").Sounds.SlingshotSound.Playing = true
end)



m:Button("Звук покупки",function(table)
    game:GetService("ReplicatedStorage").Sounds.Stock.Playing = true
end)



m:Button("Удар сосиской",function(table)
    game:GetService("ReplicatedStorage").Sounds.WeakPunch.Playing = true
end)



m:Button("Превращение в амогуса",function(table)
    game:GetService("ReplicatedStorage").Sounds.amogus.Playing = true
end)



m:Button("Пиип",function(table)
    game:GetService("ReplicatedStorage").Sounds.beep.Playing = true
end)



m:Button("Взрыв",function(table)
    game:GetService("ReplicatedStorage").Sounds.big_explosion.Playing = true
end)



m:Button("ГРОМКОЕ БЛЯЯЯ",function(table)
    game:GetService("ReplicatedStorage").Sounds.bl.Playing = true
end)



m:Button("Критический удар",function(table)
    game:GetService("ReplicatedStorage").Sounds.crit.Playing = true
end)



m:Button("Грустная скрипка",function(table)
    game:GetService("ReplicatedStorage").Sounds.epicfail.Playing = true
end)



m:Button("Амогус убийство",function(table)
    game:GetService("ReplicatedStorage").Sounds.ohio.Playing = true
end)

m:Button("Ошибка Stop 00000xA",function(table)
    game:GetService("ReplicatedStorage").Sounds.stop0.Playing = true
end)


m:Button("Разлом канавы",function(table)
    game:GetService("ReplicatedStorage").Sounds.WoodBreak["Lego Break Sound Effect"].Playing = true
end)


m:Button("Успешно",function(table)
   game:GetService("ReplicatedStorage").Sounds["New Roblox+ Item Notification Sound"].Playing = true
end)


m:Button("Виндоус ошибка",function(table)
    game:GetService("ReplicatedStorage").Sounds.Error["error sound"].Playing = true
end)


m:Button("Удар по попе",function(table)
    game:GetService("ReplicatedStorage").Sounds.trip["CalebCity Punch Sound"].Playing = true
end)


m:Button("Звонок в двери",function(table)
    game:GetService("ReplicatedStorage").Sounds.trip["Motorola Hello Moto Notification"].Playing = true
end)


m:Button("Успешно2",function(table)
    game:GetService("ReplicatedStorage").Sounds.winding.Playing = true
end)

m:Toggle("Анекдоты (Бесконечно)",function(t)
    if t then
        game:GetService("ReplicatedStorage").EmoteSounds.Untitled.Playing = true
    else
        game:GetService("ReplicatedStorage").EmoteSounds.Untitled.Playing = false
    end
end)


m:Toggle("Бетономешалка",function(t)
    if t then
        game:GetService("ReplicatedStorage").EmoteSounds.Betonomeshalka.Playing = true
    else
        game:GetService("ReplicatedStorage").EmoteSounds.Betonomeshalka.Playing = false
    end
end)


m:Toggle("Хеликоптер",function(t)
    if t then
        game:GetService("ReplicatedStorage").EmoteSounds.Helikopter.Playing = true
    else
        game:GetService("ReplicatedStorage").EmoteSounds.Helikopter.Playing = false
    end
end)

m:Toggle("Азино",function(t)
    if t then
        game:GetService("ReplicatedStorage").EmoteSounds.Azino.Playing = true
    else
        game:GetService("ReplicatedStorage").EmoteSounds.Azino.Playing = false
    end
end)

s:Toggle("Админ панель",function(t)
    if t then
        game:GetService("Players").LocalPlayer.PlayerGui.UI.AdminPanel.Visible = true
    else
        game:GetService("Players").LocalPlayer.PlayerGui.UI.AdminPanel.Visible = false
    end
end)

s:Toggle("Репорты",function(t)
    if t then
        game:GetService("Players").LocalPlayer.PlayerGui.UI.CCFrame.Visible = true
    else
        game:GetService("Players").LocalPlayer.PlayerGui.UI.CCFrame.Visible = false
    end
end)

s:Toggle("Геймпассы",function(t)
    if t then
        game:GetService("Players").LocalPlayer.PlayerGui.UI.PassFrame.Visible = true
    else
        game:GetService("Players").LocalPlayer.PlayerGui.UI.PassFrame.Visible = false
    end
end)


s:Toggle("Чёрный скрин",function(t)
    if t then
        game:GetService("Players").LocalPlayer.PlayerGui.PostUI.Black.Visible = true
    else
        game:GetService("Players").LocalPlayer.PlayerGui.PostUI.Black.Visible = false
    end
end)


s:Toggle("Дискорд разработчика + код",function(t)
    if t then
        game:GetService("Players").LocalPlayer.PlayerGui.UI.MiscDialog.Visible = true
    else
        game:GetService("Players").LocalPlayer.PlayerGui.UI.MiscDialog.Visible = false
    end
end)

s:Toggle("Меню вип",function(t)
    if t then
        game:GetService("Players").LocalPlayer.PlayerGui.UI.VIPFrame.Visible = true
    else
        game:GetService("Players").LocalPlayer.PlayerGui.UI.VIPFrame.Visible = false
    end
end)
