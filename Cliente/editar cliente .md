{
  "id": "cf8e789e-6a7d-46fe-b29e-6473a4186b23",
  "version": "2.0",
  "name": "editar cliente",
  "url": "https://sistemalift1.com",
  "tests": [{
    "id": "c2e52339-8e85-4c45-b10b-b60a8cb260d2",
    "name": "Untitled",
    "commands": [{
      "id": "cd5d74fc-18b8-41f5-9955-77fbeffe7161",
      "comment": "",
      "command": "open",
      "target": "/lifthomolog/Inicio.aspx",
      "targets": [],
      "value": ""
    }, {
      "id": "30ef79aa-54f0-4476-adb3-7e6e66644300",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "24bb5eb8-08b9-4d22-b51a-593f28287237",
      "comment": "",
      "command": "click",
      "target": "css=.DivBotao3 > a:nth-child(1) > img",
      "targets": [
        ["css=.DivBotao3 > a:nth-child(1) > img", "css:finder"],
        ["xpath=//img[@alt='Abrir Cadastro de Clientes']", "xpath:img"],
        ["xpath=//form[@id='formInicio']/table/tbody/tr[3]/td/table/tbody/tr/td/div/div/div/a/img", "xpath:idRelative"],
        ["xpath=//a/img", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "fa1e5d02-f2f1-43df-b73d-157337e2e4f1",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_btn_verTodos",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_btn_verTodos", "id"],
        ["name=ctl00$ContentPlaceHolder1$btn_verTodos", "name"],
        ["css=#ctl00_ContentPlaceHolder1_btn_verTodos", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_btn_verTodos']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input[3]", "xpath:idRelative"],
        ["xpath=//fieldset/input[3]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f669eaa8-e95b-4269-bdb5-81f4379e5f1a",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_txt_buscar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_txt_buscar", "id"],
        ["name=ctl00$ContentPlaceHolder1$txt_buscar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_txt_buscar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_txt_buscar']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input", "xpath:idRelative"],
        ["xpath=//fieldset/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "cd076df4-79bc-42c7-ae78-89bd616e9aa7",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_txt_buscar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_txt_buscar", "id"],
        ["name=ctl00$ContentPlaceHolder1$txt_buscar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_txt_buscar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_txt_buscar']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input", "xpath:idRelative"],
        ["xpath=//fieldset/input", "xpath:position"]
      ],
      "value": "igorr"
    }, {
      "id": "23f7c6c4-6715-42d1-b689-c77e8d5dea98",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_btn_ok",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_btn_ok", "id"],
        ["name=ctl00$ContentPlaceHolder1$btn_ok", "name"],
        ["css=#ctl00_ContentPlaceHolder1_btn_ok", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_btn_ok']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input[2]", "xpath:idRelative"],
        ["xpath=//fieldset/input[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "25f168a1-dfe5-4df4-a28a-5d5e0525f3e7",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome", "id"],
        ["css=#ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome", "css:finder"],
        ["xpath=//span[@id='ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome']", "xpath:attributes"],
        ["xpath=//table[@id='ctl00_ContentPlaceHolder1_grid_cliente']/tbody/tr[2]/td/a/span", "xpath:idRelative"],
        ["xpath=//a/span", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "93db1767-1dc2-446b-b91e-cdf85d0b555a",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_btn_editar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_btn_editar", "id"],
        ["name=ctl00$ContentPlaceHolder1$btn_editar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_btn_editar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_btn_editar']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_pnl_dados']/fieldset/fieldset/center/input", "xpath:idRelative"],
        ["xpath=//center/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "6c62ef7c-3423-4fa7-b3e0-c6c38fe48ff8",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_txt_nome']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "1c259e77-f12d-43cf-8df4-16bb4b2e1ede",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_txt_nome']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": "igorr b"
    }, {
      "id": "a04b4b52-bb2d-4f6c-89a9-ea79bb40fa09",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_txt_cpf",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_txt_cpf", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$txt_cpf", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_txt_cpf", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_txt_cpf']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[5]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[5]/td[2]/input", "xpath:position"]
      ],
      "value": "105.056.869-96"
    }, {
      "id": "1865b780-7075-4e7e-840c-f721455f433a",
      "comment": "",
      "command": "click",
      "target": "css=tr:nth-child(5) > td:nth-child(2)",
      "targets": [
        ["css=tr:nth-child(5) > td:nth-child(2)", "css:finder"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[5]/td[2]", "xpath:idRelative"],
        ["xpath=//tr[5]/td[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2ba71f2a-03e6-4134-b813-2266c5faccdc",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_btn_endereco",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_btn_endereco", "id"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_btn_endereco", "css:finder"],
        ["xpath=(//a[contains(text(),'Não \n                Encontrou? Clique aqui e cadastre.')])[2]", "xpath:link"],
        ["xpath=//a[@id='ctl00_ContentPlaceHolder1_FormCliente1_btn_endereco']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[19]/td[2]/a", "xpath:idRelative"],
        ["xpath=//a[contains(@href, \"javascript:__doPostBack('ctl00$ContentPlaceHolder1$FormCliente1$btn_endereco','')\")]", "xpath:href"],
        ["xpath=//tr[19]/td[2]/a", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "87f5c259-5502-4b6e-bc76-15afd0603f8b",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormClienteEndereco1$txt_cep", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/div/fieldset/div/table/tbody/tr[4]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[4]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "4b574092-896b-4915-a646-dd4487ab2b40",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormClienteEndereco1$txt_cep", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormClienteEndereco1_txt_cep']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/div/fieldset/div/table/tbody/tr[4]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[4]/td[2]/input", "xpath:position"]
      ],
      "value": "86300-000"
    }, {
      "id": "2e24582a-85a4-4229-8e43-037bfd7cc0b1",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormClienteEndereco1$btn_cadastrar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/div/fieldset/div/table/tbody/tr[12]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[12]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "73ce44c4-3ac3-4cb0-a7f9-c1dd3757c80f",
      "comment": "",
      "command": "click",
      "target": "css=tr:nth-child(5) a",
      "targets": [
        ["css=tr:nth-child(5) a", "css:finder"],
        ["xpath=(//a[contains(text(),'Selecionar')])[4]", "xpath:link"],
        ["xpath=//table[@id='ctl00_ContentPlaceHolder1_FormClienteEndereco1_grid_endereco']/tbody/tr[5]/td/a", "xpath:idRelative"],
        ["xpath=//a[contains(@href, \"javascript:__doPostBack('ctl00$ContentPlaceHolder1$FormClienteEndereco1$grid_endereco','Select$3')\")]", "xpath:href"],
        ["xpath=//tr[5]/td/a", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "189d5110-57b9-4bdb-8bd0-6a71dc4b0374",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormClienteEndereco1$btn_cadastrar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_cadastrar']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/div/fieldset/div/table/tbody/tr[12]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[12]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ab82f085-7ce5-4948-a227-00a866895108",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_voltar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_voltar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormClienteEndereco1$btn_voltar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_voltar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormClienteEndereco1_btn_voltar']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/div/fieldset/div/table/tbody/tr[12]/td[2]/input[2]", "xpath:idRelative"],
        ["xpath=//td[2]/input[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ebf55b62-8621-41df-a852-89558f5ca538",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$drp_endereco", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "css:finder"],
        ["xpath=//select[@id='ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[19]/td[2]/select", "xpath:idRelative"],
        ["xpath=//tr[19]/td[2]/select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2c4f7120-319e-4f4c-a355-3d6e531687ab",
      "comment": "",
      "command": "select",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco",
      "targets": [],
      "value": "label=Entrega1"
    }, {
      "id": "79487c9b-82d5-4609-8c3d-ce95ca6d96c8",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$drp_endereco", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "css:finder"],
        ["xpath=//select[@id='ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[19]/td[2]/select", "xpath:idRelative"],
        ["xpath=//tr[19]/td[2]/select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "407a583a-13e8-423b-9c9a-59da47222183",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$drp_endereco", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "css:finder"],
        ["xpath=//select[@id='ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[19]/td[2]/select", "xpath:idRelative"],
        ["xpath=//tr[19]/td[2]/select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f808e72b-5459-4324-bb55-7edb07305e77",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$drp_endereco", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco", "css:finder"],
        ["xpath=//select[@id='ctl00_ContentPlaceHolder1_FormCliente1_drp_endereco']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[19]/td[2]/select", "xpath:idRelative"],
        ["xpath=//tr[19]/td[2]/select", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "9530651d-61a4-46f2-9da0-f6a6cea7468b",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$btn_cadastrar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[22]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[22]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "eb18b9ed-03d8-4f3c-a84a-148fae185867",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_txt_buscar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_txt_buscar", "id"],
        ["name=ctl00$ContentPlaceHolder1$txt_buscar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_txt_buscar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_txt_buscar']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input", "xpath:idRelative"],
        ["xpath=//fieldset/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "7dede01b-6b09-4ffa-854c-d9ee626df310",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_txt_buscar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_txt_buscar", "id"],
        ["name=ctl00$ContentPlaceHolder1$txt_buscar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_txt_buscar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_txt_buscar']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input", "xpath:idRelative"],
        ["xpath=//fieldset/input", "xpath:position"]
      ],
      "value": "igorr b"
    }, {
      "id": "a32c878c-7823-47f6-84f5-5e72306e5d12",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_btn_ok",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_btn_ok", "id"],
        ["name=ctl00$ContentPlaceHolder1$btn_ok", "name"],
        ["css=#ctl00_ContentPlaceHolder1_btn_ok", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_btn_ok']", "xpath:attributes"],
        ["xpath=//div[@id='Lista']/fieldset/input[2]", "xpath:idRelative"],
        ["xpath=//fieldset/input[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "766e1dcb-fb24-4446-8a80-c78f08748f21",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome", "id"],
        ["css=#ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome", "css:finder"],
        ["xpath=//span[@id='ctl00_ContentPlaceHolder1_grid_cliente_ctl02_lbl_nome']", "xpath:attributes"],
        ["xpath=//table[@id='ctl00_ContentPlaceHolder1_grid_cliente']/tbody/tr[2]/td/a/span", "xpath:idRelative"],
        ["xpath=//a/span", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "6d2f9d7c-5ec1-444e-83c1-33a76bac3df1",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_btn_editar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_btn_editar", "id"],
        ["name=ctl00$ContentPlaceHolder1$btn_editar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_btn_editar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_btn_editar']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_pnl_dados']/fieldset/fieldset/center/input", "xpath:idRelative"],
        ["xpath=//center/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "7e92040c-c280-43db-95f9-d4003ba7ec94",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_txt_nome']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "ee001439-32dd-4c9c-9a0c-11fcb0b38d21",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_txt_nome']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": "igorr"
    }, {
      "id": "a337ea12-1d94-4473-96fb-4c4c34befc90",
      "comment": "",
      "command": "click",
      "target": "css=tr:nth-child(3) > td:nth-child(2)",
      "targets": [
        ["css=tr:nth-child(3) > td:nth-child(2)", "css:finder"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[3]/td[2]", "xpath:idRelative"],
        ["xpath=//tr[3]/td[2]", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "0c8d4aa7-5248-40ec-abbf-11c899306d73",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormCliente1$btn_cadastrar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormCliente1_btn_cadastrar']", "xpath:attributes"],
        ["xpath=//div[@id='ctl00_ContentPlaceHolder1_FormCliente1_DivFundo']/table/tbody/tr[22]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[22]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "2d5f4174-45dd-404a-ab10-66be494f1ae2",
      "comment": "",
      "command": "assertAlert",
      "target": "Nenhum registro encontrado! Por favor, tente novamente.",
      "targets": [],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "0a827364-2156-4c7f-8dea-9182d871b8dc",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["c2e52339-8e85-4c45-b10b-b60a8cb260d2"]
  }],
  "urls": ["https://sistemalift1.com/"],
  "plugins": []
}