Config = {
    ['Team'] = "Pirates", 
    ['Webhook'] = '',--doesnt done yet
    ['Panic Mode'] = {true, 3000, 5500}, -- enabled, from, to
    ['Ultra Gay Gun Mode'] = true, -- spamming gun when enemy is holding skill, etc (recm to use long-range gun like acidum rifle ( DONT USE KABUCHA PLEASE))
    ['Weapon'] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Z"] = {true,0.7,0}, -- enable, hold (3rd field doesnt done yet)
            ["X"] = {true,0.4,0},
            ["C"] = {true,0.3,0}
        },
        ["Blox Fruit"] = { 
            ["Enable"] = false,
            ["Z"] = {true,.1,0},
            ["X"] = {true,0,0},
            ["C"] = {true,0,1},
            ["V"] = {false,0,1},
            ["F"] = {true,0,1}
        },
        ["Gun"] = {
            ["Enable"] = true,
            ["Z"] = {true,0,1},
            ["X"] = {true,0,1}
        },
        ["Sword"] = {
            ["Enable"] = false,
            ["Z"] = {true,1,0},
            ["X"] = {true,1,0}
        }
    }, 
    ["Stun Moves"] = {
        ["Melee"] = {"Z"}, --DOESNT DONE
        ["Stunning Before Fight"] = true
    }
}

repeat wait() until game:IsLoaded() and game.Players.LocalPlayer 

loadstring(game:HttpGet[[https://api.eltrul.xyz/files/AutoBountyElChuaGayGayGay.lua]])()
