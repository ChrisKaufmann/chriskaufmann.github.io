---
title: "Family Tree"
date: 2021-01-24 10:11
permalink: /family-tree
---

<div id="chart_div" style="width: 140%; height: 140%;"></div>

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js">
</script>
<script type="text/javascript">
      google.charts.load('current', {packages:["orgchart"]});
      google.charts.setOnLoadCallback(drawChart);

      function drawChart() {
        var data = new google.visualization.DataTable();
        data.addColumn('string', 'Name');
        data.addColumn('string', 'Descendent');
        data.addColumn('string', 'ToolTip');

        // For each orgchart box, provide the name, manager, and tooltip to show.
        data.addRows([
['Henry J Horney 1920-2001','','US'],
['Marion C Beringer 1920-2019','','US'],
['Phillip Lee Horney 1991-2963','Henry J Horney 1920-2001','US'],
['Edith Allene Barnes 1881-1936','Henry J Horney 1920-2001','US'],
['Joel T Horney 1849-1929','Phillip Lee Horney 1991-2963',''],
['Jennie Lawrence 1854-1912','Phillip Lee Horney 1991-2963',''],
['Henry Allan Barnes 1843-','Edith Allene Barnes 1881-1936',''],
['Laura C Sloats 1851-1918','Edith Allene Barnes 1881-1936',''],
['Charles Nikolas Beringer 1884-1944','Marion C Beringer 1920-2019',''],
['Cecilia Elizabeth Haas 1892-1985','Marion C Beringer 1920-2019',''],
['Nikolas Beringer 1856-1916','Charles Nikolas Beringer 1884-1944','France'],
['Catherina Frising 1859-1946','Charles Nikolas Beringer 1884-1944','Luxembourg'],
['Joseph J Haas 1863-1932','Cecilia Elizabeth Haas 1892-1985',''],
['Catherine Louen 1867-1947','Cecilia Elizabeth Haas 1892-1985',''],

['Phillip Horney 1808-1883','Joel T Horney 1849-1929',''],
['Dorcas McKee 1814-1899','Joel T Horney 1849-1929',''],
['Emmett Van Allen Barnes 1811-1895','Henry Allan Barnes 1843-',''],
['Harriet Nawell Baldwin 1815-1888','Henry Allan Barnes 1843-',''],
['Jean Beringer 1823-1873','Nikolas Beringer 1856-1916',''],
['Anne Muller 1828-1883','Nikolas Beringer 1856-1916',''],
['Clement Frising 1836-1908','Catherina Frising 1859-1946','Luxembourg'],
['Catharina Lucas 1836-1911','Catherina Frising 1859-1946','Luxembourg'],
['Valentine Haas','Joseph J Haas 1863-1932','Germany'],
['Michael Louen 1831-','Catherine Louen 1867-1947','Prussia, Germany'],
['Elizabeth Hessler 1839','Catherine Louen 1867-1947','Prussia, Germany'],

['Manlove Horney 1782-1832','Phillip Horney 1808-1883','North Carolina, US'],
['Lydia Smith 1782-1844','Phillip Horney 1808-1883','North Carolina, US'],
['William McKee 1782-1851','Dorcas McKee 1814-1899','Kentucky, US'],
['Cassandra Frakes 1782-1867','Dorcas McKee 1814-1899','Pennsylvania, US'],
['Henri Frising 1810-1895','Clement Frising 1836-1908','Folschette, Redange, Luxembourg'],
['Anna Maria Putz','Clement Frising 1836-1908','Roodt-les-Ell, Redange, Luxembourg'],
['Mathias Lucas 1803-1882','Catharina Lucas 1836-1911','Bettendorf, Diekirch, Luxembourg'],
['Catharina Bastendorf 1809-1887','Catharina Lucas 1836-1911','Fouhren, Vianden, Luxembourg'],
['Valentine Haas','Joseph J Haas 1863-1932','Germany'],

['Phillip Horney 1758-1820','Manlove Horney 1782-1832','Caroline, Maryland, British Colony'],
['Sarah Manlove 1756-1795','Manlove Horney 1782-1832','Caroline, Somerset, Maryland, British Colony'],
['Jeffrey Horney II 1720-1779','Phillip Horney 1758-1820','Talbot, Maryland, British Colony'],
['Deborah Baynard 1716-1792','Phillip Horney 1758-1820','Queen Annes, Maryland, British Colony'],
['William Manlove 1730-1804','Sarah Manlove 1756-1795','Kent, Delaware, US'],
['Hanna Robinson 1730-1786','Sarah Manlove 1756-1795','Kent, Delaware, US'],
['Alexander H Smith 1747-1828','Lydia Smith 1782-1844','Randolph, North Carolina, US'],
['Keziah Lamar 1754-1838','Lydia Smith 1782-1844','Prince George s, Maryland, US'],
['David Smith 1720-1787','Alexander H Smith 1747-1828','Richmond, Virginia, US'],
['Anne Bryant 1723-1805','Alexander H Smith 1747-1828','Farnham, Richmond, Virginia, US'],
['James Lamar Sr. 1724-1786','Keziah Lamar 1754-1838','Prince George s, Maryland, US'],
['Verlinda Osborne 1725-1760','Keziah Lamar 1754-1838','Prince George s, Maryland, US'],

['James M\'Kee 1756-1830','William McKee 1782-1851','Cumberland, Pennsylvania, US'],
['Agnes Dickson 1750-1793','William McKee 1782-1851','Franklin, Pennsylvania, US'],
['Hugh M\'Kee 1728-1795','James M\'Kee 1756-1830','Snyder, Pennsylvania, US'],
['Mary Nesbit 1732-1795','James M\'Kee 1756-1830','Franklin, Pennsylvania, US'],
['Andrew Dickson 1712-1783','Agnes Dickson 1750-1793','Tioga, Pennsylvania, US'],
['Agnes Hill 1711-1770','Agnes Dickson 1750-1793','Franklin, Pennsylvania, US'],
['Henry Frakes IV 1760-1801','Cassandra Frakes 1782-1867','Pennsylvania, British Colony'],
['Hannah Daugherty 1765-1814','Cassandra Frakes 1782-1867','Baltimore, Maryland, British Colony'],
['Henry Frigg Frakes III 1734-1801','Henry Frakes IV 1760-1801','Bedford, Pennsylvania, British Colony'],
['Eleanor Watkins 1740-1798','Henry Frakes IV 1760-1801','Greene, Pennsylvania, British Colony'],
['Hugh Daughergy 1740-1765','Hannah Daugherty 1765-1814','Virginia, British Colony'],
['Hannah Conahan 1745-','Hannah Daugherty 1765-1814','Ireland'],

['Jeffrey Horney I 1675-1738','Jeffrey Horney II 1720-1779','Talbot, Maryland, British Colony'],
['Elizabeth Harwood 1675-1737','Jeffrey Horney II 1720-1779','Talbot, Maryland, British Colony'],
['Geoffrey Horney 1640-1711','Jeffrey Horney I 1675-1738','Talbot, Maryland, British Colony'],
['Mrs Julianna Horney 1643-1717','Jeffrey Horney I 1675-1738','Talbot, Maryland, British Colony'],
['Peter Harwood 1633-1765','Elizabeth Harwood 1675-1737','Virginia, British Colony'],
['William Baynard 1684-1729','Deborah Baynard 1716-1792','Talbot, Maryland, British Colony'],
['Susannah Pardo 1695-','Deborah Baynard 1716-1792','Maryland, British Colony'],
['John Baynard 1640-1705','William Baynard 1684-1729','Blagdon, Somerset, England'],
['Elizabeth Blackwell 1662-1691','William Baynard 1684-1729','Talbot, Maryland, British Colony'],

['Mark Manlove II 1701-1730','William Manlove 1730-1804','Delaware, British Colony'],
['Elizabeth Browne 1703-1748','William Manlove 1730-1804','Kent, Delaware, British Colony'],
['Mark Manlove 1677-1748','Mark Manlove II 1701-1730','Kent, Delaware, British Colony'],
['Margeret Hart 1679-1726','Mark Manlove II 1701-1730','Sussex, Delaware, British Colony'],
['Daniel Browne 1680-1725','Elizabeth Browne 1703-1748','Delaware, British Colony'],
['Elizabeth Pemberton 1680-1725','Elizabeth Browne 1703-1748','Sussex, Delaware, British Colony'],
['Daniel Robbison 1708-1765','William Manlove 1730-1804','Kent, Delaware, British Colony'],
['Patience Willson 1710-','William Manlove 1730-1804','Kent, Delaware, British Colony'],
['George Robbison 1690-1733','Daniel Robbison 1708-1765','Kent, Delaware, British Colony'],
['Mary Walton','Daniel Robbison 1708-1765',''],

['William Smith 1697-1743','David Smith 1720-1787','Wrightstown, Bucks, Pennsylvania, British Colony'],
['Mary Ruddle','David Smith 1720-1787',''],
['Robert Smith 1675-1738','William Smith 1697-1743','Glastonbury, Somerset, England'],
['John Bryan 1694-1736','Anne Bryant 1723-1805','Richmond, Virginia, British Colony'],
['Anne \'Anna\' Millikan 1700-1785','Anne Bryant 1723-1805','Bergen, New Jersey, British Colony'],
['Thomas Bryant Sr 1669-1717','John Bryan 1694-1736','Virginia, British Colony'],
['Eleanor 1669-1719','John Bryan 1694-1736','Rappahannock, Virginia, British Colony'],

['Thomas Lamar II 1670-1749','James Lamar Sr. 1724-1786','Prince George\'s, Maryland, British Colony'],
['Martha Blanford 1682-1755','James Lamar Sr. 1724-1786','Prince George Co, Maryland, British Colony'],
['Thomas Lamar 1641-1714','Thomas Lamar II 1670-1749','Anjoy, Isere, Rhone-Alpes, France'],
['Mary Ann Pottinger 1639-1716','Thomas Lamar II 1670-1749','Calvert, Maryland, British Colony'],
['Thomas J Blandford 1648-1698','Martha Blanford 1682-1755','Dorset, England'],
['Tabitha Wright 1647-1701','Martha Blanford 1682-1755','Calvert, Cecil, Maryland, British Colony'],
['Richard Osborne 1675-','Verlinda Osborne 1725-1760','Prince George\'s, Maryland, British Colony'],
['Frances Cooke 1709-1769','Verlinda Osborne 1725-1760','Maryland, British Colony'],

['Thomas M\'Kee Farmer and Indian Trader 1688-','Hugh M\'Kee 1728-1795','Antrim, Ireland'],
['Mary Raised by Shawnees 1705-','Hugh M\'Kee 1728-1795','Virginia, British Colony'],
['Alexander M\'Kee 1668-1740','Thomas M\'Kee Farmer and Indian Trader 1688-','Country Antrim, Ireland'],
['Mrs Alexander M\'Kee 1672-','Thomas M\'Kee Farmer and Indian Trader 1688-','Country Antrim, Ireland'],
['Thomas Nesbit','Mary Nesbit 1732-1795',''],
['Jean Nesbit','Mary Nesbit 1732-1795',''],

['George Dickson 1690-1783','Andrew Dickson 1712-1783','Edinburgh, Midlothian, Scotland'],
['Janette Elder 1690-','Andrew Dickson 1712-1783','Scotland'],
['John Dickson 1654-','George Dickson 1690-1783','Edinburgh, Midlothian, Scotland'],
['Jean Robertsone 1654-','George Dickson 1690-1783','Dunfermline, Fife, Scotland'],
['Alexander Hill 1689-','Agnes Hill 1711-1770',''],
['Margaret Mitchell 1689-1746','Agnes Hill 1711-1770','Dunfermline, Fife, Scotland'],
['David Waugh 1655-','Alexander Hill 1689-','Dysart, Fife, Scotland'],
['Isobell Williamson 1640-','Alexander Hill 1689-','Dysart, Fife, Scotland'],
['Thomas Mitchell 1660-','Margaret Mitchell 1689-1746',''],
['Marion Mudie 1664-','Margaret Mitchell 1689-1746',''],

['Henry Friggs Frakes II 1693-1784','Henry Frigg Frakes III 1734-1801','Somerset, Montgomery, Maryland, British Colony'],
['Sarah 1706-','Henry Frigg Frakes III 1734-1801','Potomac River Valley, Maryland, British Colony'],
['Henry Friggs Frakes I 1665-1716','Henry Friggs Frakes II 1693-1784','Somerset, Montgomery, Maryland, British Colony'],
['Mary Robinson-Nobles 1676-1723','Henry Friggs Frakes II 1693-1784','Somerset, Montgomery, Maryland, British Colony'],
['Evan Watkins Sr 1710-1765','Eleanor Watkins 1740-1798','Prince Edward, Virginia, British Colony'],
['Mary Catherine Webb 1710-1764','Eleanor Watkins 1740-1798','Uley, Gloucestershire, England'],
['Peter James Watkins 1689-1745','Evan Watkins Sr 1710-1765','Talbot, Maryland, British Colony'],
['Mary Griffith 1689-1745','Evan Watkins Sr 1710-1765','New Castle, Delaware, British Colony'],
['John Webb 1686-','Mary Catherine Webb 1710-1764','Uley, Gloucestershire, England'],
['Alice Howell 1678-','Mary Catherine Webb 1710-1764','Uley, Gloucestershire, England'],

['Godfrey Horne 1595-1660','Geoffrey Horney 1640-1711','Kirkburton, Yorkshire, England'],
['Ellen Boothroyd 1598-1652','Geoffrey Horney 1640-1711','Kirkburton, Yorkshire, England'],
['Richardus Horne 1560-1617','Godfrey Horne 1595-1660','Kirkburton, Yorkshire, England'],
['Anna Heptonstall 1563-','Godfrey Horne 1595-1660','Nether, York, England'],
['Henry Boothroyd 1570-','Ellen Boothroyd 1598-1652','Kirkburton, Yorkshire, England'],

['Thomas Baynard 1613-1691','John Baynard 1640-1705','Blagdon Manor, Somersetshire, England'],
['Mary Bennett 1606-1673','John Baynard 1640-1705','Northamptonshire, England'],
['Thomas Baynard 1587-1652','Thomas Baynard 1613-1691','Blagdon Manor, Somersetshire, England'],
['Martha Prickman 1587-1683','Thomas Baynard 1613-1691','Somerset, England'],
['Thomas Bennett 1600-','Mary Bennett 1606-1673','Somersetshire, England'],
['Alice Pearce Sneale 1600-1647','Mary Bennett 1606-1673',''],
['Capt. John Blackwell Sr 1646-1688','Elizabeth Blackwell 1662-1691','Barnstable Massachusetts Bay, British Colony'],
['Sarah Warren 1649-1690','Elizabeth Blackwell 1662-1691','Plymouth, Massachusetts Bay, British Colony'],
['Michael Blackwell 1616-1710','Capt. John Blackwell Sr 1646-1688','Norfolk, England'],
['Unknown 1622-1709','Capt. John Blackwell Sr 1646-1688',''],
['Nathaniel Warren 1625-1667','Sarah Warren 1649-1690','Plymouth, Massachusetts Bay, British Colony'],
['Sarah Walker 1622-1700','Sarah Warren 1649-1690','Southwark, Surrey, England'],

['Robert Horne 1535-','Richardus Horne 1560-1617','Kirkburton, Yorkshire, England'],
['Franciscae 1544-','Richardus Horne 1560-1617','England'],

['Henry Baynard 1562-1621','Thomas Baynard 1587-1652','Cullerne, Wilts, England'],
['Anne Hobbes 1570-1639','Thomas Baynard 1587-1652','Blagdon, Somerset, England'],
['Thomas Baynard 1530-1608','Henry Baynard 1562-1621','Lackham House, Lacock, Wiltshire, England'],
['Elizabeth Barnes 1534-','Henry Baynard 1562-1621','St Mary, Wanstraw, Somerset, England'],
['Thomas Hobbes 1540-','Anne Hobbes 1570-1639','Stogursey, Somerset, England'],
['Elizabeth Webber','Anne Hobbes 1570-1639','Brompton Ralph, Somerset, England'],
['Richard Prickman 1588-','Martha Prickman 1587-1683','Blagdon, Somerset, England'],
['Mrs Richard Prickman 1592-','Martha Prickman 1587-1683','Blagdon, Somerset, England'],


['Richard Warren -1628','Nathaniel Warren 1625-1667','England <a href="https://en.wikipedia.org/wiki/Richard_Warren">Mayflower</a>'],
['Elizabeth Walker 1583-1673','Nathaniel Warren 1625-1667','Hertfordshire, England'],
['Christopher Warren 1546-1587','Richard Warren -1628','Cornwall, England'],
['Alice Webb 1559-1586','Richard Warren -1628','Devon, England'],
['Augustine Walker 1550-1614','Elizabeth Walker 1583-1673','Hertfordshire, England'],
['Elizabeth 1551-1614','Elizabeth Walker 1583-1673','Hertfordshire, England'],
['William Walker 1620-1703','Sarah Walker 1622-1700','Lancashire, England'],
['Sarah Snow 1632-1703','Sarah Walker 1622-1700','Plymouth, Massachusetts, British Colony'],
['William Walker 1565-1625','William Walker 1620-1703','Lancashire, England'],
['Jane Margaret Clark 1592-1625','William Walker 1620-1703','London, England'],
['Nicholas Snow 1599-1676','Sarah Snow 1632-1703','England'],
['Constance Hopkins 1606-1677','Sarah Snow 1632-1703','Hampshire, England'],

['Robert Baynard 1500-1537','Thomas Baynard 1530-1608','Wiltshire, England'],
['Ann Blake 1496-','Thomas Baynard 1530-1608','Wiltshire, England'],
['Philip Baynard 1471-1522','Robert Baynard 1500-1537','Wiltshire, England'],
['Jane Stukeley 1483-1513','Robert Baynard 1500-1537','Devon, England'],
['Robert Blake 1436-1515','Ann Blake 1496-','Wiltshire, England'],
['Margaret Englefield 1440-1500','Ann Blake 1496-','Wiltshire, England'],
['George Barnes 1510-','Elizabeth Barnes 1534-','Berks, England'],
['Mrs. George Barnes 1514-','Elizabeth Barnes 1534','Berks, England'],

['Michael Blackwell 1600-1700','Michael Blackwell 1616-1710','England'],
['Unknown 1600-1700','Michael Blackwell 1616-1710','Yorkshire, England'],


['William De Warren 1532-1559','Christopher Warren 1546-1587','Devon, England'],
['Ann Margaret Mable 1525-1562','Christopher Warren 1546-1587','Cornwall, England'],
['Thomas John Richmond 1529-1560','Alice Webb 1559-1586','Devon, England'],
['Edetha Marie Calne Grene 1519-1609','Alice Webb 1559-1586','Wiltshire, England'],
['Christopher Warren 1476-1531','William De Warren 1532-1559','Cheshire, England'],
['Lady Margaret Jane Leigh 1518-1575','William De Warren 1532-1559','Lancashire, England'],
['Thomas Mable 1489-1581','Ann Margaret Mable 1525-1562','Cornwall, England'],
['Mrs. Thomas Mable 1505-','Ann Margaret Mable 1525-1562','Cornwall, England'],
['Mr Mable 1494-','Thomas Mable 1489-1581','Cornwall, England'],
['Mrs Mable 1498-','Thomas Mable 1489-1581','Cornwall, England'],

['John Warren 1459-1522','Christopher Warren 1476-1531','Devon, England'],
['Eleanor Gerard 1467-1561','Christopher Warren 1476-1531','Devon, England'],
['Sir Peter Piers Leigh 1442-1527','Lady Margaret Jane Leigh 1518-1575','Cheshire, England'],
['Lady Margery Radclyffe 1461-1528','Lady Margaret Jane Leigh 1518-1575','Lancashire, England'],
['Lawrence de Warren 1435-1474','John Warren 1459-1522','England'],
['Mrs Lawrence Warren 1425-1475','John Warren 1459-1522','Cheshire, England'],
['Gerard 1544-','Eleanor Gerard 1467-1561','Dorset, England'],
['Mrs. Gerard 1544-','Eleanor Gerard 1467-1561','Dorset, England'],
['Peter Piers de Leigh 1389-1422','Sir Peter Piers Leigh 1442-1527','Cheshire, England'],
['Margaret Danvers 1348-1428','Sir Peter Piers Leigh 1442-1527','Cheshire, England'],
['Sir John Radcliffe 1414-1485','Lady Margery Radclyffe 1461-1528','Lancashire, England'],
['Isabel Tyldesley 1433-1513','Lady Margery Radclyffe 1461-1528','Lancashire, England'],

['Sir John Hutchinson Walker 1530-1576','Augustine Walker 1564-1614','Warwickshire, England'],
['Katherine Bicknill 1535-1562','Augustine Walker 1564-1614','Warwickshire, England'],
['Sir John Thomas Walker I 1495-1575','Sir John Hutchinson Walker 1530-1576','Warwickshire, England'],
['Anne Chelscombe 1500-1576','Sir John Hutchinson Walker 1530-1576','Warwickshire, England'],
['William E. Bicknell I 1513-1599','Katherine Bicknill 1535-1562','Warwickshire, England'],
['Mary De Forte 1503-1564','Katherine Bicknill 1535-1562','Worchestershire, England'],

['William Waller Sheriff van Kent 1470-1555','Sir John Thomas Walker I 1495-1575','Kent, England'],
['Lady Anna Symons Waller 1470-1542','Sir John Thomas Walker I 1495-1575','Hampshire, England'],
['Lord Thomas Chelescombe 1475-1560','Anne Chelscombe 1500-1576','Hertfordshire, England'],
['Margaret Allan 1480-1500','Anne Chelscombe 1500-1576','Warwickshire, England'],
['Sir Knight John Henry Waller 1435-1517','William Waller Sheriff van Kent 1470-1555','Kent, England'],
['Johanna Whitehall 1444-','William Waller Sheriff van Kent 1470-1555','Kent, England'],
['Sir William Willem Falleumar Falconer 1440-1490','Lady Anna Symons Waller 1470-1542','Hampshire, England'],
['Anne Lady Palmer 1443-1495','Lady Anna Symons Waller 1470-1542','London, England'],
['N.N. Cleynaert -','Lord Thomas Chelescombe 1475-1560','Warwickshire, England'],
['Joffrouw Isabella Cleijnaels 1450-1520','Lord Thomas Chelescombe 1475-1560','Noord-Brabant, Nederland'],

['','',''],
        ]);

        // Create the chart.
        var chart = new google.visualization.OrgChart(document.getElementById('chart_div'));
        // Draw the chart, setting the allowHtml option to true for the tooltips.
        chart.draw(data, {'allowHtml':true,'allowCollapse':true});
      }
</script>
