# Lights_Off


/** Game board of Lights out.  *  * Properties:  *  * - nrows: number of rows of board  * - ncols: number of cols of board  * - chanceLightStartsOn: float, chance any cell is lit at start of game  *  * State:  *  * - hasWon: boolean, true when board is all off  * - board: array-of-arrays of true/false  *  *    For this board:  *       .  .  .  *       O  O  .     (where . is off, and O is on)  *       .  .  .  *  *    This would be: [[f, f, f], [t, t, f], [f, f, f]]  *  *  This should render an HTML table of individual <Cell /> components.  *  *  This doesn't handle any clicks --- clicks are on individual cells  *  **/
