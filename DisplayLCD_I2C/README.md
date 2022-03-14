# DisplayLCD_I2C

Programa

## :warning: Biblioteca

- Funcionalidades
  - HD44780_Init(uint8_t rows);
  - HD44780_Clear();
  - HD44780_Home();
  - HD44780_NoDisplay();
  - HD44780_Display();
  - HD44780_NoBlink();
  - HD44780_Blink();
  - HD44780_NoCursor();
  - HD44780_Cursor();
  - HD44780_ScrollDisplayLeft();
  - HD44780_ScrollDisplayRight();
  - HD44780_PrintLeft();
  - HD44780_PrintRight();
  - HD44780_LeftToRight();
  - HD44780_RightToLeft();
  - HD44780_ShiftIncrement();
  - HD44780_ShiftDecrement();
  - HD44780_NoBacklight();
  - HD44780_Backlight();
  - HD44780_AutoScroll();
  - HD44780_NoAutoScroll();
  - HD44780_CreateSpecialChar(uint8_t, uint8_t[]);
  - HD44780_PrintSpecialChar(uint8_t);
  - HD44780_SetCursor(uint8_t, uint8_t);
  - HD44780_SetBacklight(uint8_t new_val);
  - HD44780_LoadCustomCharacter(uint8_t char_num, uint8_t *rows);
  - HD44780_PrintStr(const char[]);

## :hammer: Configurações

- Configurações do `DISPLAY`:
  - `DEVICE_ADDR`: Endereço do módulo I2C `default 0x27`;
**NOTA:** Diretiva `define` encontrada no arquivo [liquidcrystal_i2c.h](./Core/Inc/liquidcrystal_i2c.h):
## 🔥 Como usar?

1. Baixe o `projeto` via git clone;
2. Importe a pasta no `STM32CubeIDE`;
3. Aperte `Ctrl + B` para criar o build da aplicação.
