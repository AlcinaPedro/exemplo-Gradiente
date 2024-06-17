var grad = ctnxt.createLinearGradient(0, 0, 200, 0);
                var gradInf = cntxt.createLinearGradient(0, 0, 200, 0)
            var gradR = cntxt.createRadialGradient(300, 100, 15, 300, 100, 100)
        vargradInf = cntxt.createRadialGradient (300, 300, 15, 300, 300, 100)    
    
    grad.addColorStop(0, "Red");
grad.addColorStop(1, "rgb(0, 0, 255")
gradInf.addColorStop(0, "rgb(120, 10, 10)");
                    gradInf.addColorStop(0.5, "rgb(10, 120, 10)");
                    gradInf.addColorStop(1, "rgb(10, 10, 120)");

                    gradR.addColorStop(0, "green");
                    gradR.addColorStop(1, "rgb(255, 0, 0)");

                    gradInf.addColorStop(0, "#0000ff");
                    gradInf.addColorStop(0.25, "#ffff00");
                    gradInf.addColorStop(0.5,"00ff00");
                    gradInf.addColorStop(0.75, "#ff0000");
                    gradInf.addColorStop(1, "#ffffff");

                    // superior square
                    cntxt.beginPath();
                    cntxt.fillStyle = grad;
                    cntxt.fillRect(5, 5, 105, 100);
                    cntxt.stroke();
                    cntxt.closePath();

                    // left inferior eye 
                    cntxt.beginPath();
                    cntxt.fillStyle = gradInf;
                    cntxt.moveTo(10, 300);
                    cntxt.quadraticCurveTo(100, 200, 190, 300);
                    cntxt.fill();
                    cntxt.stroke();
                    cntxt.beginpath();
                    cntxt.moveTo(10, 300);
                    cntxt.quadraticcurveTo(100, 400, 190, 300);
                    cntxt.fill();
                    cntxt.stroke();
                    cntxt.closePath();
                    
                    // circulo superior direito /
                    cntxt.beginpath();
                    cntxt.fillStyle -gradR;
                    cntxt.arc(300, 100, 97, 0 Math.PI * 2, true);
                    cntxt.fill();
                    cntxt.stroke();
                    cntxt.closepath();

                    // Olho inferior direito /
                    cntxt.beginpath();
                    cntxt.fillStyle = gradRinf;
                    cntxt.moveTo(210, 300);
                    cntxt.quadraticCurveTo(300, 200,  390, 300
                    cntxt.fill();
                    cntxt.stroke();
                    cntxt.beginpath();
                    cntxt.moveTo(210, 300);
                    cntxt.quadraticCurveTo(300, 400, 390, 300)
                    cntxt.fill();
                    cntxt.stroke();
                    cntxt.closePath();
                        
                    )
                    
                }                