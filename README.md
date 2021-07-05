I change imx7d-pico.dtsi with 
  pinctrl-names =3D "default";
	pinctrl-0 =3D <&pinctrl_hog>;

AND gpio00 - gpio66

I change imx7d-pico-pi.dts with

&iomuxc {
	pinctrl-names =3D "default";
	pinctrl-0 =3D <&pinctrl_hog>;
  
  LOOK to 3D
