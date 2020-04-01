# Joystick

A joystick (hand controller, gamepad, etc) when connected to the topside controller is how the user provides control inputs to the vehicle. These inputs may be in the form of movement (stick control) or action items (button presses).

QGroundControl has support for Microsoft's [XInput Game Controller API](https://docs.microsoft.com/en-us/windows/win32/xinput/xinput-game-controller-apis-portal) meaning any controller which supports XInput may be used.

QgroundControl supports controllers with up to 4 control axes and 16 buttons.

# Supported Commercial Joysticks

The following joysticks have been tested and are supported:

* [Logitech F310](https://www.logitechg.com/en-us/products/gamepads/f310-gamepad.940-000110.html) (wired)
* [Logitech F710](https://www.logitechg.com/en-us/products/gamepads/f710-wireless-gamepad.html) (wireless)
* [Microsoft Xbox One controllers](https://www.xbox.com/en-US/accessories/controllers/xbox-black-wireless-controller) (wired and wireless)
* [Sony PlayStation 4 controllers](https://www.playstation.com/en-us/explore/accessories/gaming-controllers/dualshock-4/) (wired only)

# Custom Joysticks

With the inclusion of industry standard drivers and APIs, custom controllers can be built using a joystick control board and standard buttons and sticks. 

Marine Simulation wrote a quick tutorial on how to do so: [Custom Hand Controller Design](http://marinesimulation.com/custom-hand-controller-design/)

The following control boards have been known to work:

* [Leo Bodnar Electronics](https://www.leobodnar.com/shop/)
    * [BU0836X 12-Bit Joystick Board](http://www.leobodnar.com/shop/index.php?main_page=product_info&cPath=94&products_id=180)
    * [BU0836A 12-Bit Joystick Controller](http://www.leobodnar.com/shop/index.php?main_page=product_info&cPath=94&products_id=204)
    * [BU0836A-NC 12-Bit Joystick Controller No Connectors](http://www.leobodnar.com/shop/index.php?main_page=product_info&cPath=94&products_id=219)
* [Ultimarc](https://www.ultimarc.com/)
    * [Mini-PAC Standard](https://www.ultimarc.com/control-interfaces/mini-pac-en/mini-pac/)

## Custom Joystick Examples
