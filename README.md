I change imx7d-pico.dtsi with 
  pinctrl-names =3D "default";
	pinctrl-0 =3D <&pinctrl_hog>;

AND gpio00 - gpio66

I change imx7d-pico-pi.dts with

&iomuxc {
	pinctrl-names =3D "default";
	pinctrl-0 =3D <&pinctrl_hog>;
  
  LOOK to 3D:
  
  http://next.patchew.org/Linux/20201201074125.11806-1-o.rempel@pengutronix.de/mbox
  
  Changes were based on the link above
