{
  "id": "4deece9b-a56d-48cc-922f-6a69322ce446",
  "version": "2.0",
  "name": "editar funcionario",
  "url": "https://sistemalift1.com/lifthomolog/Inicio.aspx",
  "tests": [{
    "id": "373f3ed1-88aa-4183-bfdc-49595851b28b",
    "name": "Untitled",
    "commands": [{
      "id": "546d6310-9139-4bdd-88d0-57766d680e1f",
      "comment": "",
      "command": "open",
      "target": "https://sistemalift1.com/lifthomolog/Inicio.aspx",
      "targets": [],
      "value": ""
    }, {
      "id": "50fae178-5406-48bd-ad86-fd4320a48a3c",
      "comment": "",
      "command": "setWindowSize",
      "target": "1382x744",
      "targets": [],
      "value": ""
    }, {
      "id": "c9ea40af-5be1-4c38-b89f-5bcf40fbba49",
      "comment": "",
      "command": "click",
      "target": "css=.DivBotaoEmpresa > a:nth-child(1) > img",
      "targets": [
        ["css=.DivBotaoEmpresa > a:nth-child(1) > img", "css:finder"],
        ["xpath=//img[@alt='Abrir Cadastro de Funcionários da Empresa']", "xpath:img"],
        ["xpath=//form[@id='formInicio']/table/tbody/tr[3]/td/table/tbody/tr/td[2]/div/div/div/a/img", "xpath:idRelative"],
        ["xpath=//td[2]/div/div/div/a/img", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "d54de774-b0dd-4bc8-8af2-a6e081680c2e",
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
      "id": "86ba0a2f-42e7-4a87-a580-a504dd84e0e9",
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
      "value": "gabriel"
    }, {
      "id": "2bc38b78-3de1-4dc2-89dd-e0452f67b05a",
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
      "id": "3b7ec679-ddf5-4e32-9b85-7ca012030a8b",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome", "id"],
        ["css=#ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome", "css:finder"],
        ["xpath=//span[@id='ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome']", "xpath:attributes"],
        ["xpath=//table[@id='ctl00_ContentPlaceHolder1_grid_funcionario']/tbody/tr[2]/td/a/span", "xpath:idRelative"],
        ["xpath=//a/span", "xpath:position"],
        ["xpath=//span[contains(.,'GABRIEL')]", "xpath:innerText"]
      ],
      "value": ""
    }, {
      "id": "4149d14f-eeb2-444d-b483-8479872d3591",
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
      "id": "2b17753f-6000-4d19-9f3e-c417432520f4",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormFuncionario1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/fieldset/div/div/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "dcc87ba8-e18c-4b25-a55c-5f96f0cf1f53",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormFuncionario1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/fieldset/div/div/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": "GABRIEL kik"
    }, {
      "id": "c61fcb1a-aa8c-4001-9001-19dc4fa82c8f",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormFuncionario1$btn_cadastrar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/fieldset/div/div/table/tbody/tr[20]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[20]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "bfce8a63-298c-4d5e-b1a9-885deb45de17",
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
      "id": "dd0f14a6-3095-4a63-8653-3c9eb47acb71",
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
      "value": "gabriel kik"
    }, {
      "id": "2576665d-c3c0-46d8-81ee-3d8d0b73f4f4",
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
      "id": "1891eddf-6656-4544-9892-41113ace1a7e",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome", "id"],
        ["css=#ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome", "css:finder"],
        ["xpath=//span[@id='ctl00_ContentPlaceHolder1_grid_funcionario_ctl02_lbl_nome']", "xpath:attributes"],
        ["xpath=//table[@id='ctl00_ContentPlaceHolder1_grid_funcionario']/tbody/tr[2]/td/a/span", "xpath:idRelative"],
        ["xpath=//a/span", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "e56a32e8-6df8-4b9f-9fc1-a0b564c06ba0",
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
      "id": "329128d5-f918-45cf-9b62-95c3f0e63b7a",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormFuncionario1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/fieldset/div/div/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "fc0fdb12-a91a-4cbd-b3f1-03e2c2d4fa72",
      "comment": "",
      "command": "type",
      "target": "id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormFuncionario1$txt_nome", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormFuncionario1_txt_nome']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/fieldset/div/div/table/tbody/tr/td[2]/input", "xpath:idRelative"],
        ["xpath=//td[2]/input", "xpath:position"]
      ],
      "value": "GABRIEL"
    }, {
      "id": "7be0aacf-d2b3-4c03-b842-7857985734c1",
      "comment": "",
      "command": "click",
      "target": "id=aspnetForm",
      "targets": [
        ["id=aspnetForm", "id"],
        ["name=aspnetForm", "name"],
        ["css=#aspnetForm", "css:finder"],
        ["xpath=//form[@id='aspnetForm']", "xpath:attributes"],
        ["xpath=//body[@id='ctl00_body']/form", "xpath:idRelative"],
        ["xpath=//form", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "f1e4406d-6f75-4a75-bef9-aa307d81adce",
      "comment": "",
      "command": "click",
      "target": "id=ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar",
      "targets": [
        ["id=ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar", "id"],
        ["name=ctl00$ContentPlaceHolder1$FormFuncionario1$btn_cadastrar", "name"],
        ["css=#ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar", "css:finder"],
        ["xpath=//input[@id='ctl00_ContentPlaceHolder1_FormFuncionario1_btn_cadastrar']", "xpath:attributes"],
        ["xpath=//form[@id='aspnetForm']/table/tbody/tr[3]/td/fieldset/div/div/table/tbody/tr[20]/td[2]/input", "xpath:idRelative"],
        ["xpath=//tr[20]/td[2]/input", "xpath:position"]
      ],
      "value": ""
    }, {
      "id": "32ccd26b-4e0f-4974-ae2e-4eb4a5972f50",
      "comment": "",
      "command": "assertAlert",
      "target": "Nenhum registro encontrado! Por favor, tente novamente.",
      "targets": [],
      "value": ""
    }]
  }],
  "suites": [{
    "id": "2ee59298-c62f-49a1-874f-21635bc48d5f",
    "name": "Default Suite",
    "persistSession": false,
    "parallel": false,
    "timeout": 300,
    "tests": ["373f3ed1-88aa-4183-bfdc-49595851b28b"]
  }],
  "urls": ["https://sistemalift1.com/", "https://sistemalift1.com/lifthomolog/Inicio.aspx"],
  "plugins": []
}