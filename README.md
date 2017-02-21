//  ViewController.swift
import UIKit
class ViewController: UIViewController {

    
    
    
    override func viewDidLoad() {
        super.viewDidLoad()
        
        print( "字面常數 mapd 同學" )
        // fix 練習 #1  demo: 執行此程式, 觀察下ㄧ行會印出什麼?
        print(/* 拾進位	*/   19)
        /* 取得字面常數代表的值, 再把值印出來 */
        // fix 練習 #2  demo: 執行此程式, 觀察下ㄧ行會印出什麼?
        print(/* 拾進位	*/   20)
        /* 取得字面常數代表的值, 再把值印出來 */
        // fix 練習 #3  demo: 執行此程式, 觀察下ㄧ行會印出什麼?
        print(/* 拾六進位	*/   0x19 )
        /* 取得字面常數代表的值, 再把值印出來 */
        print("###########25")
        // fix 練習 #4   lab: 執行此程式, 觀察下ㄧ行會印出什麼?
        // fix 練習 #5   lab: 修改下ㄧ行, 使得可用拾六進位 表達拾進位 26 的值
        print(/* 拾六進位	*/   0x20 )
        /* 取得字面常數代表的值, 再把值印出來 */
        print("###########32")
        
        // fix 練習 #6  demo: 執行此程式, 觀察下ㄧ行會印出什麼?
        print(/* 八進位	*/   0o17 ) /* 取得字面常數代表的值, 再把值印出來 */
        print("##########15")
        // fix 練習 #7   lab: 將下ㄧ行註解取消, 看會如何?
        // fix 練習 #8   lab: 修改下ㄧ行, 使得可用八進位 表達拾進位 16 的值也可印出來
        print(/* 八進位 */   0o21 )/*取得字面常數代表的值,再把值印出來*/
        print("###########17")
        // fix 練習 #9   demo: 執行此程式, 觀察下ㄧ行會印出什麼?
        print(/* 二進位	*/   0b11 ) /* 取得字面常數代表的值, 再把值印出來 */
        print("###########3")
        // fix 練習 #10   lab: 將下ㄧ行註解取消, 看會如何?
        // fix 練習 #11   lab: 修改下ㄧ行,使得可用二進位 表達拾進位 4 的值
         print(/* 二進位	*/   0b100 )/*取得字面常數代表的值,再把值印出來*/
        print("###########4")
        // fix 練習 #12   lab: 將下三行註解取消, 看會如何?
        // fix 練習 #13   lab: 修改下三行, 使得可印出
//甘迺迪說:"Do NOT ask what your country can do for you",說完就走了
print(
 "甘迺迪說:\"Do NOT ask what your country can do for you\",說完就走了"
        )
        // fix 練習 #14   demo: 執行此程式, 觀察上三行會印出什麼?
        
        var iLoveYou:Bool = true
        print("###########")
        // fix 練習 #15   lab: 將下ㄧ行註解取消, 看會如何?
        // iLoveYou = false
        // fix 練習 #16   demo: 執行此程式, 觀察下ㄧ行會印出什麼?
         print( iLoveYou )
        
        print( "以上, MAPD 同學" )
    }

    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        //
    }

}
