<h1>DOCOMO</h1>

## FORMALIZATION II

Elements in ~~strikethrough~~ are not in effect and are left only for historical reference.

### Definitions

  - ~~Elements~~
    - ~~An element is the smallest indivisible unit of a documental resource~~
    - ~~The following elements are defined:~~
      - ~~Paragraph~~
  - Components
    - A component is a distinguishable unit of a documental resource
  - Types
    - A type is a common name given to distinct components
    - The following types are defined:
      - Documental resource
      - Sentence
      - Paragraph
      - Block of text
      - Identifier
      - Digit
  - Properties
    - A property is a proposition which is defined for a type or set of types, and which is asserted to be true for 
      particular components of such type
      - Each property is notated with the prefix "Is"
    - The following properties are defined:
        <table>
            <tr>
                <th>Property</th>
                <th>Defined types</th>
                <th>Definition</th>
            </tr>
            <tr>
                <td>IsParent</td>
                <td>Paragraph</td>
                <td>Whether the paragraph is a parent</td>
            </tr>
            <tr>
                <td>IsTitle</td>
                <td>Paragraph</td>
                <td>Whether the paragraph is parentless</td>
            </tr>
            <tr>
                <td>IsOrdered</td>
                <td>Block of text</td>
                <td>Whether the block of text is a sequence</td>
            </tr>
            <tr>
                <td>IsSeparator</td>
                <td>Digit</td>
                <td>Whether the digit belongs to the documental resource's separator digits set</td>
            </tr>
            <tr>
                <td>IsDigital</td>
                <td>Identification</td>
                <td>Whether the elements of the identification are non-separator digits</td>
            </tr>
        </table>
  - Auxiliary types
    - Auxiliary types are types not related to the subject matter of the formalization; that is, documental resources
    - The following auxiliary types are defined:
      - Set
      - Ordered set
      - Sequence
      - Ordered pair
      - Relation
      - Symbol

### Type definitions

A definition that is an axiom is not given; instead being open to interpretation.

The following definitions are given in dependency order.

<table>
    <tr>
        <th>Type</th>
        <th>Is auxiliary?</th>
        <th>Definition</td>
    </tr>
    <tr>
        <td>Set</td>
        <td>Yes</td>
        <td>A collection of unique elements</td>
    </tr>
    <tr>
        <td>Documental resource</td>
        <td>No</td>
        <td>The set of all components under consideration</td>
    </tr>
    <tr>
        <td>Sentence</td>
        <td>No</td>
        <td><i>Axiom</i></td>
    </tr>
    <tr>
        <td>Ordered set</td>
        <td>Yes</td>
        <td>A set of ordered elements</td>
    </tr>
    <tr>
        <td>Sequence</td>
        <td>Yes</td>
        <td>An ordered set that admits duplicate elements</td>
    </tr>
    <tr>
        <td>Paragraph</td>
        <td>No</td>
        <td>A sequence of sentences</td>
    </tr>
    <tr>
        <td>Ordered pair</td>
        <td>Yes</td>
        <td>An ordered set containing two elements</td>
    </tr>
    <tr>
        <td>Relation</td>
        <td>Yes</td>
        <td>A set of ordered pairs of paragraphs</td>
    </tr>
    <tr>
        <td>Block of text</td>
        <td>No</td>
        <td>A set of paragraphs sharing the same related paragraph under the parenthood relation</td>
    </tr>
    <tr>
        <td>Identifier</td>
        <td>No</td>
        <td>A sequence of non-separator digits or symbols that is unique across a documental resource</td>
    </tr>
    <tr>
        <td>Symbol</td>
        <td>Yes</td>
        <td>A uniquely named discrete entity</td>
    </tr>
    <tr>
        <td>Digit</td>
        <td>No</td>
        <td>A symbol</td>
    </tr>
</table>