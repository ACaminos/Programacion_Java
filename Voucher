Insumos
package ventasinsumo;

/* @author Ariel Caminos*/

public class Insumos {

   public int MemoriaRAM1Gb;
   public int MemoriaRAM2Gb;
   public int MemoriaRAM3Gb;
   public int MemoriaRAM4Gb;
   public int PlacaVideo1Gb;
   public int PlacaVideo2GB;
   public int PlacaVideo3Gb;
   public int PlacaVideo4Gb;
   public int Pendrive4Gb;
   public int Pendrive8Gb;
   public int Pendrive16Gb;
   public int Pendrive32Gb;
   public int Pendrive64Gb;
   public int CartuchoImpresoraNegro;
   public int CartuchoImpresoraColor;
   public int TonnerImpresora;    
}
-----------------------------------------------------------------------------------------------------------------------
Carrito
package ventasinsumo;

/**
 *
 * @author Ariel Caminos
 */
public class Carrito {

    public int CarritoMemoria;
    public int CarritoPlaca;
    public int CarritoPendrive;
    public int CarritoCartucho;
    
}

------------------------------------------------------------------------------------------------------------------------
Cliente
package ventasinsumo;

/* @Author Ariel Caminos */

public class Cliente {
   public String Nombre;
   public String Apellido;
   public int DNI;
   public int Voucher = 5000;
}
------------------------------------------------------------------------------------------------------------------------

package ventasinsumo;

import javax.swing.JOptionPane;

/**
 *
 * @author Ariel Caminos
 */
public class VentasInsumo {


    public static void main(String[] args) {
        int opcion;
        int opcionMemoria;
        int OpcionPlaca;
        int OpcionPendrive;
        int OpcionCartucho;
        int repetir;
        int SumaTotal;
        int MasOpciones;
        int resto;
        
        Insumos insumos1 = new Insumos ();
        insumos1.MemoriaRAM1Gb = 100;
        insumos1.MemoriaRAM2Gb = 200;
        insumos1.MemoriaRAM3Gb = 300;
        insumos1.MemoriaRAM4Gb = 400;
        insumos1.PlacaVideo1Gb = 300;
        insumos1.PlacaVideo2GB = 400;
        insumos1.PlacaVideo3Gb = 500;
        insumos1.PlacaVideo4Gb = 600;
        insumos1.Pendrive4Gb = 89;
        insumos1.Pendrive8Gb = 178;
        insumos1.Pendrive16Gb = 356;
        insumos1.Pendrive32Gb = 712;
        insumos1.Pendrive64Gb = 1424;
        insumos1.CartuchoImpresoraNegro = 1500;
        insumos1.CartuchoImpresoraColor = 1200;
        insumos1.TonnerImpresora = 3500;
        
        Cliente cliente1 = new Cliente ();
        cliente1.Nombre = "";
        cliente1.Apellido = "";
        cliente1.DNI = 0;
        cliente1.Voucher = 5000;
        
        Carrito carrito1 = new Carrito();
        carrito1.CarritoCartucho = 0;
        carrito1.CarritoMemoria = 0;
        carrito1.CarritoPlaca = 0;
        carrito1.CarritoPendrive = 0;
        
        cliente1.Nombre = JOptionPane.showInputDialog("Bienvenido al sistema de Ventas de insumos. Por favor Ingrese su nombre");
        JOptionPane.showMessageDialog(null, "\t\t¡"+cliente1.Nombre+ "! \n\t¡Usted a ganado un Voucher por $5000!");
       

 JOptionPane.showMessageDialog(null, "Sr/a "+cliente1.Nombre+" a continuacion se le presentará un menú con los insumos que usted desee comprar y canjear su Voucher");
        do{
        opcion = Integer.parseInt(JOptionPane.showInputDialog("Ingrese la opción deseada:\n1- Memorias RAM\n2- Placas de video\n3- Pendrive\n4- Tinta de impresora"));
        switch (opcion){
            case 1:
                do{
                    opcionMemoria = Integer.parseInt(JOptionPane.showInputDialog("1- Memoria RAM de 1 Giga\t $100\n2- Memoria RAM de 2 Gigas\t $200\n3- Memoria RAM de 3 Gigas\t $300\n4- Memoria RAM de 4 Gigas\t $400\n"));
                    switch (opcionMemoria){
                        case 1:
                            carrito1.CarritoMemoria= carrito1.CarritoMemoria + insumos1.MemoriaRAM1Gb;
                            break;
                        case 2:
                            carrito1.CarritoMemoria= carrito1.CarritoMemoria + insumos1.MemoriaRAM2Gb;
                            break;
                        case 3:
                            carrito1.CarritoMemoria= carrito1.CarritoMemoria + insumos1.MemoriaRAM3Gb;
                            break;
                        case 4:
                            carrito1.CarritoMemoria= carrito1.CarritoMemoria + insumos1.MemoriaRAM4Gb;
                            break;
                        default:
                            JOptionPane.showMessageDialog(null, "Usted a ingresado un valor inexistente");
                            break;
                                        }
                            repetir = Integer.parseInt(JOptionPane.showInputDialog("¿Desea comprar algun producto mas de ésta sección?\n1- Si\n2- No\n"));
                    }
                            while (repetir ==1);
                            break;
                        case 2:
                            do {
                                OpcionPlaca = Integer.parseInt(JOptionPane.showInputDialog("1- Placa de Video 1 Giga\t $300\n2- Placa de Video 2 Gigas\t $400\n3- Placa de Video 3 Gigas\t $500\n"));
                                switch (OpcionPlaca){
                                    case 1:
                                        carrito1.CarritoPlaca = carrito1.CarritoPlaca + insumos1.PlacaVideo1Gb;
                                        break;
                                    case 2:
                                        carrito1.CarritoPlaca = carrito1.CarritoPlaca + insumos1.PlacaVideo2GB;
                                        break;
                                    case 3:
                                        carrito1.CarritoPlaca = carrito1.CarritoPlaca + insumos1.PlacaVideo3Gb;
                                        break;
                                    default:
                                        JOptionPane.showMessageDialog(null, "Usted a ingresado un valor inexistente");
                                        break;
                                                    }
                                repetir = Integer.parseInt(JOptionPane.showInputDialog("¿Desea comprar algun producto mas de ésta sección?\n1-Si\n2- No\n"));
                                }
                            while (repetir == 1);
                            break;
                
	               case 3:
                            do{
                                OpcionPendrive = Integer.parseInt(JOptionPane.showInputDialog("1- Pendrive 4 Gigas\t $89\n2- Pendrive 8 Gigas\t $178\n3- Pendrive 16 Gigas\t $356\n4- Pendrive 32 Gigas\t $712\n5- Pendrive 64 Gigas\t $1424"));
                                switch (OpcionPendrive){
                                    case 1:
                                        carrito1.CarritoPendrive = carrito1.CarritoPendrive + insumos1.Pendrive4Gb;
                                        break;
                                    case 2:
                                        carrito1.CarritoPendrive = carrito1.CarritoPendrive + insumos1.Pendrive8Gb;
                                        break;
                                    case 3:
                                        carrito1.CarritoPendrive = carrito1.CarritoPendrive + insumos1.Pendrive16Gb;
                                        break;
                                    case 4:
                                        carrito1.CarritoPendrive = carrito1.CarritoPendrive + insumos1.Pendrive32Gb;
                                        break;
                                    case 5:
                                        carrito1.CarritoPendrive = carrito1.CarritoPendrive + insumos1.Pendrive64Gb;
                                        break;
                                    default:
                                        JOptionPane.showMessageDialog(null, "Usted a ingresado un valor inexistente");
                                        break;
                                }
                                repetir = Integer.parseInt(JOptionPane.showInputDialog("¿Desea comprar algun producto más de ésta sección?\n1- Si\n2- No\n"));
                            }
                            while (repetir == 1);
                            break;
                        case 4:
                            do{
                                OpcionCartucho = Integer.parseInt(JOptionPane.showInputDialog("1- Cartucho impresora tinta NEGRA\t $1500\n2- Cartucho impresora tinta COLOR\t $1200\n3 Toner NEGRO impresora laser\t $3500\n"));
                                switch (OpcionCartucho){
                                    case 1:
                                        carrito1.CarritoCartucho = carrito1.CarritoCartucho + insumos1.CartuchoImpresoraNegro;
                                        break;
                                    case 2:
                                        carrito1.CarritoCartucho = carrito1.CarritoCartucho + insumos1.CartuchoImpresoraColor;
                                        break;
                                    case 3:
                                        carrito1.CarritoCartucho = carrito1.CarritoCartucho + insumos1.TonnerImpresora;
                                        break;
                                    default:
                                        JOptionPane.showMessageDialog(null, "Usted a ingresado un valor inexistente");
                                        break;
                                                        }
                                repetir = Integer.parseInt(JOptionPane.showInputDialog("¿Desea comprar algun producto más de ésta sección?\n1- Si\n2- No\n"));
                                }
                            while (repetir == 1);
                        default:
                       
		   JOptionPane.showMessageDialog(null, "¡ Opción inexistente !");
                            break;
                        }
        MasOpciones = Integer.parseInt(JOptionPane.showInputDialog("¿Desea seleccionar otra opcion?\n1-  Si\n2- No\n"));
        }
        while (MasOpciones == 1);
        
        SumaTotal = carrito1.CarritoCartucho + carrito1.CarritoMemoria + carrito1.CarritoPendrive + carrito1.CarritoPlaca;
        
        if (SumaTotal <= 5000)
                {
                resto = 5000 - SumaTotal;
                JOptionPane.showMessageDialog(null, "El valor total de su carrito es $"+SumaTotal+ "\n\tSe procederá a facturar");
                cliente1.DNI = Integer.parseInt(JOptionPane.showInputDialog("Ingrese su DNI para emitir su factura"));
                JOptionPane.showMessageDialog(null, "\t\tComprobante Factura\n\n\nNombre:\t"+cliente1.Nombre+"\nApellido:\t"+cliente1.Apellido+"\nDNI:\t"+cliente1.DNI+"\n\n\nTotal:\t$"+SumaTotal);
                
                }
        else
                {
                JOptionPane.showMessageDialog(null, "Usted ha superado el monto del voucher, la diferencia se cobrará en efectivo");
                cliente1.DNI = Integer.parseInt(JOptionPane.showInputDialog("Ingrese su DNI para emitir su factura"));
                JOptionPane.showMessageDialog(null, "\t\tComprobante Factura\n\n\nNombre:\t"+cliente1.Nombre+"\nApellido:\t"+cliente1.Apellido+"\nDNI:\t"+cliente1.DNI+"\n\n\nTotal:\t$"+SumaTotal);
                }
                
    }
    }
